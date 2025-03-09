# Function: <code>put_online_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_online_cpus()
```

```json
{
  "name": "put_online_cpus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579374432,
      "name": "put_online_cpus",
      "external": true,
      "loc": "kernel/cpu.c:105",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:apply_workqueue_attrs",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask",
        "kernel/sched/core.c:tg_set_cfs_bandwidth",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/rcu/tree.c:_rcu_barrier",
        "kernel/cpuset.c:rebuild_sched_domains_locked",
        "kernel/stop_machine.c:stop_machine",
        "kernel/kprobes.c:force_unoptimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:lockup_detector_resume",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_cpumask",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_set_cpumasks",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_add_cpu",
        "kernel/padata.c:padata_remove_cpu",
        "mm/swap.c:lru_add_drain_all",
        "mm/vmstat.c:vmstat_start",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_cpuup_callback",
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_create",
        "mm/slab_common.c:kmem_cache_create",
        "mm/slab_common.c:kmem_cache_create",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:memcg_destroy_kmem_caches",
        "mm/memcontrol.c:try_charge",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_cst_has_changed",
        "drivers/net/virtio_net.c:virtnet_set_channels",
        "drivers/cpufreq/cpufreq.c:store",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/core/flow.c:flow_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374432,
      "name": "put_online_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_online_cpus()
```

```json
{
  "name": "put_online_cpus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579385776,
      "name": "put_online_cpus",
      "external": true,
      "loc": "kernel/cpu.c:182",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page",
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask",
        "kernel/sched/core.c:tg_set_cfs_bandwidth",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/irq/affinity.c:irq_create_affinity_mask",
        "kernel/rcu/tree.c:_rcu_barrier",
        "kernel/cpuset.c:rebuild_sched_domains_locked",
        "kernel/stop_machine.c:stop_machine",
        "kernel/kprobes.c:force_unoptimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/watchdog.c:proc_watchdog_cpumask",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:lockup_detector_resume",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask",
        "mm/swap.c:lru_add_drain_all",
        "mm/vmstat.c:vmstat_cpuup_callback",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_start",
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_destroy_kmem_caches",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create",
        "mm/slab_common.c:kmem_cache_create",
        "mm/slab_common.c:kmem_cache_create",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/net/virtio_net.c:virtnet_set_channels",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:store",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/intel_pstate.c:store_min_perf_pct",
        "drivers/cpufreq/intel_pstate.c:store_max_perf_pct",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "net/core/flow.c:flow_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579385776,
      "name": "put_online_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_online_cpus()
```

```json
{
  "name": "put_online_cpus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579403488,
      "name": "put_online_cpus",
      "external": true,
      "loc": "kernel/cpu.c:248",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page",
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask",
        "kernel/sched/core.c:tg_set_cfs_bandwidth",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/rcu/tree.c:_rcu_barrier",
        "kernel/cpuset.c:rebuild_sched_domains_locked",
        "kernel/stop_machine.c:stop_machine",
        "kernel/kprobes.c:force_unoptimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/watchdog.c:proc_watchdog_cpumask",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:lockup_detector_resume",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask",
        "mm/swap.c:lru_add_drain_all",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_start",
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_destroy_kmem_caches",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create",
        "mm/slab_common.c:kmem_cache_create",
        "mm/slab_common.c:kmem_cache_create",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:store",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "net/core/dev.c:rollback_registered_many",
        "net/core/flow.c:flow_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403488,
      "name": "put_online_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578889442,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578904295,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596290181,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579118966,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160356,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "arch/x86/kernel/cpu/mtrr/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168289,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337295,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579506530,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:apply_workqueue_attrs",
        "kernel/workqueue.c:schedule_on_each_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579540418,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579563618,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579733160,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827653,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579846110,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:_rcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579864894,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580081978,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580218648,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_cpumask",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:lockup_detector_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580279534,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580355006,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580613719,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580630893,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580731411,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596476903,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580836326,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_destroy_kmem_caches",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_deactivate_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580862353,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581192088,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584288651,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586603095,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586612245,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586617018,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586628619,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587013976,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587164433,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:127",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578890914,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602606959,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579174938,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "arch/x86/kernel/cpu/mtrr/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579182972,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362731,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579533250,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:apply_workqueue_attrs",
        "kernel/workqueue.c:schedule_on_each_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579566633,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579593026,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579766765,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579863413,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579886754,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:_rcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579908332,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580134090,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580332702,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580408705,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580694485,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580711933,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580817459,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602803742,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580927014,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_destroy_kmem_caches",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_deactivate_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953345,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584685981,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587086371,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587095301,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587099728,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587111513,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587512383,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588256614,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:125",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578892726,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602775284,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579186280,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194529,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579375121,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579560818,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:apply_workqueue_attrs",
        "kernel/workqueue.c:schedule_on_each_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579594809,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579616864,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579800990,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579897584,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579915211,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:_rcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579942635,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580195480,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580394466,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580469705,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580826289,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580843581,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602976940,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581062534,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_destroy_kmem_caches",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_deactivate_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264481,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584912178,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587384531,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587393493,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587402772,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587409977,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587856254,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588611582,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush"
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
  "name": "put_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578892918,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604570116,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175656,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183937,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402785,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579598034,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:apply_workqueue_attrs",
        "kernel/workqueue.c:schedule_on_each_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579632825,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579651648,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579847614,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579944952,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579962360,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579989723,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580244797,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580447666,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580525785,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580893057,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580913165,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604776917,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581140342,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_destroy_kmem_caches",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_deactivate_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347649,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585016066,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587564643,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587573461,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587577412,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587590057,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587996352,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
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
  "name": "put_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578893827,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604664703,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579188138,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196659,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579418224,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579621218,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579657660,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690234,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579881108,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579983605,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580001889,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580031424,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580299364,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580501928,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580582209,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580990559,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581010777,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604872247,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581205896,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581458097,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585219725,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587840419,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587849365,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587854619,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587866359,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588267899,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
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
  "name": "put_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578894867,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604677201,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579190426,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579199027,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579421402,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579647298,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579694748,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730170,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579931392,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580033749,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580052077,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580082144,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580354085,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580549736,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580629313,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044543,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581063684,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_shell",
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604906153,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581272261,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581522177,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585356157,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588045251,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588054181,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588060860,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588071591,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588474281,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
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
  "name": "put_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578899395,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609027707,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211050,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220160,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450622,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579679325,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/workqueue.c:schedule_on_each_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579734572,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579759686,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579974906,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:s2idle_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580084469,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580116717,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580142010,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580427519,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580649832,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580730269,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:start_kthread",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581223967,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245508,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_shell",
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609224414,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:all_vm_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581462210,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581729726,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586063913,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588888453,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588905539,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588913633,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588918656,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588934140,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589386192,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
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
  "name": "put_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578895395,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612091026,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579206394,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214608,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579447886,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579659453,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/workqueue.c:schedule_on_each_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579714508,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579746567,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579961757,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:s2idle_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580067045,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580098389,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580119242,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580415007,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580640172,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580719608,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:start_kthread",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581266543,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581285620,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_shell",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612291510,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:all_vm_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581497800,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581777422,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586185919,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588901605,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588918115,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588926273,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588931104,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588944268,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589349404,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:145",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:flush_all_backlogs"
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
  "name": "put_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578897964,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614230531,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208778,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614291015,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450446,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579665506,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/workqueue.c:schedule_on_each_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579721740,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579754791,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579964268,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:s2idle_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580067685,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580100325,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580122522,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580416607,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580640508,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580724698,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581285247,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581303684,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_shell",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614431167,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:all_vm_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581804990,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586061955,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588800046,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588806723,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588814465,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588819450,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588833644,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589249077,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:150",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:flush_all_backlogs"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "put_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490818288,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490874212,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490911808,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491141000,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:s2idle_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491238664,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491255020,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491611448,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491834164,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491933560,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492400420,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492421476,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_shell",
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510944508,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492677556,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492948300,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497639040,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501314096,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502000640,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "put_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224851780,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3224891760,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 3224925616,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 3225138944,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225251432,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 3225278232,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225567232,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 3225780044,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225867720,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 3226285568,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 3226305840,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_shell",
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 3243434368,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3226516056,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 3226731556,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 3233800868,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 3234765744,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "put_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282429456,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/powerpc/kernel/rtasd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/rtasd.c:rtas_event_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282981516,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/powerpc/platforms/powernv/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283081020,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/powerpc/platforms/powernv/opal-imc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/opal-imc.c:disable_core_pmu_counters",
        "arch/powerpc/platforms/powernv/opal-imc.c:disable_nest_pmu_counters"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283347632,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/powerpc/kvm/book3s_hv_builtin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kvm/book3s_hv_builtin.c:kvm_hv_vm_deactivated",
        "arch/powerpc/kvm/book3s_hv_builtin.c:kvm_hv_vm_activated"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283651344,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283706184,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283754396,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284035664,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284139400,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284174136,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284207732,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284605268,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284898620,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285031956,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285662800,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285694792,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_shell",
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302592820,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_start"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286003724,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286359788,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294847696,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294863992,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/powernv-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295436076,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "put_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272141314,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578894867,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604603473,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189274,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579197875,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417242,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579623602,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579671068,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579706826,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580002485,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580020813,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580050880,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580322885,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580518536,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580598113,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581013391,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032532,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_shell",
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604811613,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581241109,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581490913,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585157485,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587670243,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587679173,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587685852,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587693735,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588081065,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
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
  "name": "put_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578888771,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604595040,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579123946,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579132867,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346362,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579551970,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579599420,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579634686,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579838974,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579941157,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579961949,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579996192,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580270165,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580466584,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580544593,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580959519,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580978612,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_shell",
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604780674,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581187781,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581433169,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585071645,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587444115,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587452949,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587456412,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587469863,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587794633,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
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
  "name": "put_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578894803,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604681297,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579190346,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579198947,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417162,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579620882,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579668300,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579698042,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579891664,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579994021,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580012349,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580042416,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314133,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580509784,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580589361,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581004591,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581023732,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_shell",
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604888797,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581232309,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581482225,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585307741,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588001395,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588010325,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588017004,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588027735,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588412841,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
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
  "name": "put_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578895363,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604681317,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579195594,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204403,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426218,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579654546,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579702460,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579737289,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579937492,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580040757,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580067037,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580093199,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580369045,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580566120,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580646257,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581065791,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581085748,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_shell",
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604910334,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581295845,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581546977,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585413885,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588116835,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588125797,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588132476,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588143207,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588551433,
      "name": "put_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:138",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void put_online_cpus()
```
</details>
</li>
</ul>
