# Function: <code>smp_call_function_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908400,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:271",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vgetcpu_cpu_notifier",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_callback",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_callback",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback",
        "arch/x86/kernel/kvm.c:kvm_cpu_notify",
        "arch/x86/kernel/kvm.c:kvm_cpu_notify",
        "kernel/rcu/tree.c:_rcu_barrier",
        "kernel/rcu/tree.c:synchronize_sched_expedited",
        "kernel/rcu/tree.c:rcu_cpu_notify",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_many",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:task_function_call",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:perf_remove_from_context",
        "kernel/events/core.c:perf_ioctl",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/idle/intel_idle.c:cpu_hotplug_notify",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908400,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579938144,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:255",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vgetcpu_online",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_callback",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_callback",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback",
        "arch/x86/kernel/kvm.c:kvm_cpu_notify",
        "arch/x86/kernel/kvm.c:kvm_cpu_notify",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/rcu/tree.c:_rcu_barrier",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_stop",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:task_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/idle/intel_idle.c:cpu_hotplug_notify",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938144,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579968896,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:259",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vgetcpu_online",
        "arch/x86/xen/mmu.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/rcu/tree.c:_rcu_barrier",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:on_each_cpu_cond",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_stop",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:task_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579968896,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579974384,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:268",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vgetcpu_online",
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online",
        "arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/rcu/tree.c:_rcu_barrier",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:on_each_cpu_cond",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_stop",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:task_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579974384,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580020864,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:268",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vgetcpu_online",
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:apply_microcode_on_target",
        "arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/sched/membarrier.c:SyS_membarrier",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/rcu/tree.c:_rcu_barrier",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:on_each_cpu_cond",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_stop",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:task_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020864,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580074944,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:268",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vgetcpu_online",
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:apply_microcode_on_target",
        "arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:_rcu_barrier",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:on_each_cpu_cond",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_stop",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:task_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580074944,
      "name": "smp_call_function_single",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122256,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:268",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu",
        "arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:apply_microcode_on_target",
        "arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:on_each_cpu_cond_mask",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_stop",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:task_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122256,
      "name": "smp_call_function_single",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580167664,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:269",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu",
        "arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:apply_microcode_on_target",
        "arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:on_each_cpu_cond_mask",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_stop",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:task_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167664,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580215600,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:269",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu",
        "arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:apply_microcode_on_target",
        "arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:on_each_cpu_cond_mask",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_stop",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:task_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215600,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580283968,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:337",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz",
        "arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/rcu/tree.c:sync_sched_exp_online_cleanup",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_cgroup_attach",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:event_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580283968,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580267488,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:467",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu",
        "arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/rcu/tree.c:sync_sched_exp_online_cleanup",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_cgroup_attach",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:event_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "net/bpf/test_run.c:bpf_prog_test_run_raw_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267488,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580273344,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:709",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu",
        "arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/time/clocksource.c:clocksource_verify_percpu",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_cgroup_attach",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:event_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "net/bpf/test_run.c:bpf_prog_test_run_raw_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580273344,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580425376,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:709",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu",
        "arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/time/clockevents.c:unbind_device_store",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_cgroup_attach",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:event_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "net/bpf/test_run.c:bpf_prog_test_run_raw_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580425376,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580648384,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:728",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/rcu/update.c:rcu_tasks_trace_postgp",
        "kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus",
        "kernel/time/clockevents.c:unbind_device_store",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_cgroup_attach",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:event_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "net/bpf/test_run.c:bpf_prog_test_run_raw_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580648384,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580915440,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:727",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/rcu/update.c:rcu_tasks_trace_postgp",
        "kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus",
        "kernel/time/clockevents.c:unbind_device_store",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_cgroup_attach",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:event_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/intel_pstate.c:hybrid_get_cpu_scaling",
        "net/bpf/test_run.c:bpf_prog_test_run_raw_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915440,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003152,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:581",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/rcu/update.c:rcu_tasks_trace_postgp",
        "kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus",
        "kernel/time/clockevents.c:unbind_device_store",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/events/core.c:perf_cgroup_attach",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:event_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/intel_pstate.c:hwp_get_cpu_scaling",
        "net/bpf/test_run.c:bpf_prog_test_run_raw_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003152,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581099312,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:601",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/rcu/update.c:rcu_tasks_trace_postgp",
        "kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus",
        "kernel/time/hrtimer.c:hrtimers_cpu_dying",
        "kernel/time/clockevents.c:unbind_device_store",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/events/core.c:perf_cgroup_attach",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:event_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/intel_pstate.c:hwp_get_cpu_scaling",
        "net/bpf/test_run.c:bpf_prog_test_run_raw_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581099312,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491454208,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:269",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/cacheinfo.c:populate_cache_leaves",
        "arch/arm64/kernel/cacheinfo.c:init_cache_level",
        "virt/kvm/kvm_main.c:kvm_init",
        "virt/kvm/arm/arm.c:kvm_arch_init",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_stop",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:task_function_call",
        "drivers/soc/fsl/qbman/qman.c:qman_delete_cgr_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491454208,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225439624,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:269",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_dfs_request",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_stop",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:task_function_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225439624,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284403760,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:269",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/sysfs.c:store_tsr3",
        "arch/powerpc/kernel/sysfs.c:show_tsr3",
        "arch/powerpc/kernel/sysfs.c:store_tsr2",
        "arch/powerpc/kernel/sysfs.c:show_tsr2",
        "arch/powerpc/kernel/sysfs.c:store_tsr1",
        "arch/powerpc/kernel/sysfs.c:show_tsr1",
        "arch/powerpc/kernel/sysfs.c:store_tsr0",
        "arch/powerpc/kernel/sysfs.c:show_tsr0",
        "arch/powerpc/kernel/sysfs.c:store_siar",
        "arch/powerpc/kernel/sysfs.c:show_siar",
        "arch/powerpc/kernel/sysfs.c:store_sier",
        "arch/powerpc/kernel/sysfs.c:show_sier",
        "arch/powerpc/kernel/sysfs.c:store_ier",
        "arch/powerpc/kernel/sysfs.c:show_ier",
        "arch/powerpc/kernel/sysfs.c:store_ber",
        "arch/powerpc/kernel/sysfs.c:show_ber",
        "arch/powerpc/kernel/sysfs.c:store_mer",
        "arch/powerpc/kernel/sysfs.c:show_mer",
        "arch/powerpc/kernel/sysfs.c:store_der",
        "arch/powerpc/kernel/sysfs.c:show_der",
        "arch/powerpc/kernel/sysfs.c:store_rpccr",
        "arch/powerpc/kernel/sysfs.c:show_rpccr",
        "arch/powerpc/kernel/sysfs.c:store_pccr",
        "arch/powerpc/kernel/sysfs.c:show_pccr",
        "arch/powerpc/kernel/sysfs.c:store_btcr",
        "arch/powerpc/kernel/sysfs.c:show_btcr",
        "arch/powerpc/kernel/sysfs.c:store_imaat",
        "arch/powerpc/kernel/sysfs.c:show_imaat",
        "arch/powerpc/kernel/sysfs.c:store_ima9",
        "arch/powerpc/kernel/sysfs.c:show_ima9",
        "arch/powerpc/kernel/sysfs.c:store_ima8",
        "arch/powerpc/kernel/sysfs.c:show_ima8",
        "arch/powerpc/kernel/sysfs.c:store_ima7",
        "arch/powerpc/kernel/sysfs.c:show_ima7",
        "arch/powerpc/kernel/sysfs.c:store_ima6",
        "arch/powerpc/kernel/sysfs.c:show_ima6",
        "arch/powerpc/kernel/sysfs.c:store_ima5",
        "arch/powerpc/kernel/sysfs.c:show_ima5",
        "arch/powerpc/kernel/sysfs.c:store_ima4",
        "arch/powerpc/kernel/sysfs.c:show_ima4",
        "arch/powerpc/kernel/sysfs.c:store_ima3",
        "arch/powerpc/kernel/sysfs.c:show_ima3",
        "arch/powerpc/kernel/sysfs.c:store_ima2",
        "arch/powerpc/kernel/sysfs.c:show_ima2",
        "arch/powerpc/kernel/sysfs.c:store_ima1",
        "arch/powerpc/kernel/sysfs.c:show_ima1",
        "arch/powerpc/kernel/sysfs.c:store_ima0",
        "arch/powerpc/kernel/sysfs.c:show_ima0",
        "arch/powerpc/kernel/sysfs.c:store_hid5",
        "arch/powerpc/kernel/sysfs.c:show_hid5",
        "arch/powerpc/kernel/sysfs.c:store_hid4",
        "arch/powerpc/kernel/sysfs.c:show_hid4",
        "arch/powerpc/kernel/sysfs.c:store_hid1",
        "arch/powerpc/kernel/sysfs.c:show_hid1",
        "arch/powerpc/kernel/sysfs.c:store_hid0",
        "arch/powerpc/kernel/sysfs.c:show_hid0",
        "arch/powerpc/kernel/sysfs.c:store_pa6t_pmc5",
        "arch/powerpc/kernel/sysfs.c:show_pa6t_pmc5",
        "arch/powerpc/kernel/sysfs.c:store_pa6t_pmc4",
        "arch/powerpc/kernel/sysfs.c:show_pa6t_pmc4",
        "arch/powerpc/kernel/sysfs.c:store_pa6t_pmc3",
        "arch/powerpc/kernel/sysfs.c:show_pa6t_pmc3",
        "arch/powerpc/kernel/sysfs.c:store_pa6t_pmc2",
        "arch/powerpc/kernel/sysfs.c:show_pa6t_pmc2",
        "arch/powerpc/kernel/sysfs.c:store_pa6t_pmc1",
        "arch/powerpc/kernel/sysfs.c:show_pa6t_pmc1",
        "arch/powerpc/kernel/sysfs.c:store_pa6t_pmc0",
        "arch/powerpc/kernel/sysfs.c:show_pa6t_pmc0",
        "arch/powerpc/kernel/sysfs.c:store_dscr",
        "arch/powerpc/kernel/sysfs.c:show_dscr",
        "arch/powerpc/kernel/sysfs.c:store_tscr",
        "arch/powerpc/kernel/sysfs.c:show_tscr",
        "arch/powerpc/kernel/sysfs.c:store_pir",
        "arch/powerpc/kernel/sysfs.c:show_pir",
        "arch/powerpc/kernel/sysfs.c:store_spurr",
        "arch/powerpc/kernel/sysfs.c:show_spurr",
        "arch/powerpc/kernel/sysfs.c:store_purr",
        "arch/powerpc/kernel/sysfs.c:show_purr",
        "arch/powerpc/kernel/sysfs.c:store_mmcra",
        "arch/powerpc/kernel/sysfs.c:show_mmcra",
        "arch/powerpc/kernel/sysfs.c:store_pmc8",
        "arch/powerpc/kernel/sysfs.c:show_pmc8",
        "arch/powerpc/kernel/sysfs.c:store_pmc7",
        "arch/powerpc/kernel/sysfs.c:show_pmc7",
        "arch/powerpc/kernel/sysfs.c:store_pmc6",
        "arch/powerpc/kernel/sysfs.c:show_pmc6",
        "arch/powerpc/kernel/sysfs.c:store_pmc5",
        "arch/powerpc/kernel/sysfs.c:show_pmc5",
        "arch/powerpc/kernel/sysfs.c:store_pmc4",
        "arch/powerpc/kernel/sysfs.c:show_pmc4",
        "arch/powerpc/kernel/sysfs.c:store_pmc3",
        "arch/powerpc/kernel/sysfs.c:show_pmc3",
        "arch/powerpc/kernel/sysfs.c:store_pmc2",
        "arch/powerpc/kernel/sysfs.c:show_pmc2",
        "arch/powerpc/kernel/sysfs.c:store_pmc1",
        "arch/powerpc/kernel/sysfs.c:show_pmc1",
        "arch/powerpc/kernel/sysfs.c:store_mmcr1",
        "arch/powerpc/kernel/sysfs.c:show_mmcr1",
        "arch/powerpc/kernel/sysfs.c:store_mmcr0",
        "arch/powerpc/kernel/sysfs.c:show_mmcr0",
        "arch/powerpc/kernel/watchdog.c:watchdog_nmi_start",
        "arch/powerpc/kernel/watchdog.c:watchdog_nmi_stop",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_stop",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:task_function_call",
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_stop_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284403760,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271910348,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:269",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/cacheinfo.c:populate_cache_leaves",
        "arch/riscv/kernel/cacheinfo.c:init_cache_level",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_stop",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:task_function_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271910348,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580184400,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:269",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu",
        "arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:apply_microcode_on_target",
        "arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:on_each_cpu_cond_mask",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_stop",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:task_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184400,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580131904,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:269",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu",
        "arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:apply_microcode_on_target",
        "arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:on_each_cpu_cond_mask",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_stop",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:task_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/hv/channel.c:vmbus_reset_channel_cb",
        "drivers/hv/channel_mgmt.c:vmbus_add_channel_work",
        "drivers/hv/channel_mgmt.c:vmbus_add_channel_work",
        "drivers/hv/channel_mgmt.c:hv_process_channel_removal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131904,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580175872,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:269",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu",
        "arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:apply_microcode_on_target",
        "arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:on_each_cpu_cond_mask",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_stop",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:task_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580175872,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
int smp_call_function_single(int cpu, smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580227968,
      "name": "smp_call_function_single",
      "external": true,
      "loc": "kernel/smp.c:269",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu",
        "arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit",
        "arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:apply_microcode_on_target",
        "arch/x86/kernel/cpu/microcode/core.c:collect_cpu_info",
        "arch/x86/kernel/apic/vector.c:print_ICs",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:clockevents_unbind_device",
        "kernel/smp.c:on_each_cpu_cond_mask",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_stop",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:event_function_call",
        "kernel/events/core.c:task_function_call",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_regs_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsrl_on_cpu",
        "arch/x86/lib/msr-smp.c:rdmsr_on_cpu",
        "arch/x86/lib/cache-smp.c:wbinvd_on_cpu",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/cpufreq/powernow-k8.c:powernowk8_get",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580227968,
      "name": "smp_call_function_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
