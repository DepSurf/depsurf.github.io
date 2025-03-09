# Function: <code>get_online_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void get_online_cpus()
```

```json
{
  "name": "get_online_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579373904,
      "name": "get_online_cpus",
      "external": true,
      "loc": "kernel/cpu.c:93",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state",
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
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
        "kernel/watchdog.c:lockup_detector_suspend",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_cpumask",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_set_cpumasks",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_add_cpu",
        "kernel/padata.c:padata_remove_cpu",
        "mm/swap.c:lru_add_drain_all",
        "mm/vmstat.c:vmstat_start",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_cpuup_callback",
        "mm/slab_common.c:kmem_cache_shrink",
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
      "addr": 18446744071579373904,
      "name": "get_online_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void get_online_cpus()
```

```json
{
  "name": "get_online_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579383504,
      "name": "get_online_cpus",
      "external": true,
      "loc": "kernel/cpu.c:170",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page",
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
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
        "kernel/watchdog.c:lockup_detector_suspend",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
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
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/net/virtio_net.c:virtnet_set_channels",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:store",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
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
      "addr": 18446744071579383504,
      "name": "get_online_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void get_online_cpus()
```

```json
{
  "name": "get_online_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579402528,
      "name": "get_online_cpus",
      "external": true,
      "loc": "kernel/cpu.c:236",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page",
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
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
        "kernel/watchdog.c:lockup_detector_suspend",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
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
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:store",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "net/core/dev.c:rollback_registered_many",
        "net/core/flow.c:flow_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402528,
      "name": "get_online_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
  "name": "get_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578889416,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578903869,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596290108,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579118942,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160239,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "arch/x86/kernel/cpu/mtrr/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168155,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
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
      "addr": 18446744071579337175,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579506461,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
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
      "addr": 18446744071579540181,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
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
      "addr": 18446744071579563478,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579733062,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827614,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579846001,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:_rcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579864790,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580081916,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580218529,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_cpumask",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:lockup_detector_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580279480,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580354932,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580613624,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580630860,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580731401,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596476763,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
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
      "addr": 18446744071580836301,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
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
      "addr": 18446744071580862343,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581191875,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584288404,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586602965,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586612220,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586616919,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586628522,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587013837,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587164251,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:126",
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
  "name": "get_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578890888,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602606896,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579174815,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "arch/x86/kernel/cpu/mtrr/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579182857,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
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
      "addr": 18446744071579362611,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579533181,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
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
      "addr": 18446744071579566557,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579592886,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579766727,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579863374,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579886663,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:_rcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579908383,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580134028,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580332648,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580408646,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580694403,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580711900,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580817449,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602803602,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
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
      "addr": 18446744071580926989,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
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
      "addr": 18446744071580953335,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584685724,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587086261,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587095276,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587099639,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587111434,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587512257,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588256490,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:124",
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
  "name": "get_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578892700,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602775217,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579186159,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194397,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
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
      "addr": 18446744071579375011,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579560749,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
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
      "addr": 18446744071579594725,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579616503,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579800904,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579897547,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579915119,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:_rcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579942536,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580195429,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580394399,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580469647,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580826205,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580843548,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602976828,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
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
      "addr": 18446744071581062501,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
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
      "addr": 18446744071581264471,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584911908,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587384421,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587393461,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587402683,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587409877,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587856128,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588611418,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:128",
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
  "name": "get_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578892892,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604570049,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175535,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183805,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
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
      "addr": 18446744071579402675,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579597965,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
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
      "addr": 18446744071579632741,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579651287,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579847528,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579944927,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579962273,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579989624,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580243797,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580447599,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580525727,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580892973,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580913132,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604776805,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
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
      "addr": 18446744071581140309,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
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
      "addr": 18446744071581347639,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585015796,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587564533,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587573429,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587577323,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587589957,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587996226,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:130",
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
  "name": "get_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578893803,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604664634,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579188015,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196523,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
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
      "addr": 18446744071579418113,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579621149,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
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
      "addr": 18446744071579657573,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579689835,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579881018,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579983586,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580001786,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580031291,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580299292,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580501860,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580582151,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580990474,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581010748,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604872134,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
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
      "addr": 18446744071581205861,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
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
      "addr": 18446744071581458087,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585219461,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587840301,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587849333,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587854535,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587866261,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588267764,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:132",
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
  "name": "get_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578894843,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604677132,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579190303,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579198891,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071579421297,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579647229,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071579694661,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579729771,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579931302,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580033730,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580051962,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580082011,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580353957,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071580549668,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580629255,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044458,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581063668,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071604906040,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071581272151,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071581522167,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585355893,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588045133,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588054149,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588060775,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588071493,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588474146,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
  "name": "get_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578899371,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609027638,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210927,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219998,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
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
      "addr": 18446744071579450521,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579679199,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
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
      "addr": 18446744071579734485,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579759227,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579974812,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:s2idle_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580084450,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580116536,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580141883,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580427485,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
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
      "addr": 18446744071580649666,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580730232,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:start_kthread",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581223882,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245492,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_shell",
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609224301,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
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
      "addr": 18446744071581462187,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
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
      "addr": 18446744071581729677,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586063653,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588888349,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588905421,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588913617,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588918808,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588934037,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589386057,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:143",
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
  "name": "get_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578895371,
      "name": "get_online_cpus",
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
      "addr": 18446744071612090957,
      "name": "get_online_cpus",
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
      "addr": 18446744071579206271,
      "name": "get_online_cpus",
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
      "addr": 18446744071579214446,
      "name": "get_online_cpus",
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
      "addr": 18446744071579447785,
      "name": "get_online_cpus",
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
      "addr": 18446744071579659327,
      "name": "get_online_cpus",
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
      "addr": 18446744071579714421,
      "name": "get_online_cpus",
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
      "addr": 18446744071579746075,
      "name": "get_online_cpus",
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
      "addr": 18446744071579961663,
      "name": "get_online_cpus",
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
      "addr": 18446744071580067026,
      "name": "get_online_cpus",
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
      "addr": 18446744071580098216,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580119115,
      "name": "get_online_cpus",
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
      "addr": 18446744071580414973,
      "name": "get_online_cpus",
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
      "addr": 18446744071580640034,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580719571,
      "name": "get_online_cpus",
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
      "addr": 18446744071581266458,
      "name": "get_online_cpus",
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
      "addr": 18446744071581285604,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_shell",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612291397,
      "name": "get_online_cpus",
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
      "addr": 18446744071581497765,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
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
      "addr": 18446744071581777373,
      "name": "get_online_cpus",
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
      "addr": 18446744071586185621,
      "name": "get_online_cpus",
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
      "addr": 18446744071588901501,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588917997,
      "name": "get_online_cpus",
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
      "addr": 18446744071588926257,
      "name": "get_online_cpus",
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
      "addr": 18446744071588931256,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588944165,
      "name": "get_online_cpus",
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
      "addr": 18446744071589349103,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:144",
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
  "name": "get_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578897931,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614230462,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208655,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614290962,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
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
      "addr": 18446744071579450345,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579665421,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
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
      "addr": 18446744071579721653,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579754299,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579964178,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:s2idle_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580067666,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580100152,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580122395,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580416573,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
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
      "addr": 18446744071580640441,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580724661,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581285162,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581303668,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_shell",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614431051,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
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
      "addr": 18446744071581804941,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586061717,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588799942,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588806605,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588814449,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588819365,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588833541,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248767,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:149",
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
  "name": "get_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490818208,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446603336490874148,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490911364,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491140904,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:s2idle_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491238640,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491254880,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491611336,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446603336491834128,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491933500,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492400300,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492421460,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446603336510944348,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446603336492677452,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446603336492948292,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497638712,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501313936,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502000484,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
  "name": "get_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224851708,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 3224891692,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 3224925004,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 3225138852,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225251404,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 3225278052,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225567012,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 3225779968,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225867680,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 3226285456,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 3226305824,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 3243434356,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 3226516044,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 3226731548,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 3233800704,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 3234765576,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
  "name": "get_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282429340,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/powerpc/kernel/rtasd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/rtasd.c:rtas_event_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282981452,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/powerpc/platforms/powernv/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283080876,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/powerpc/platforms/powernv/opal-imc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/opal-imc.c:disable_core_pmu_counters",
        "arch/powerpc/platforms/powernv/opal-imc.c:disable_nest_pmu_counters"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283347596,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/powerpc/kvm/book3s_hv_builtin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kvm/book3s_hv_builtin.c:kvm_hv_vm_deactivated",
        "arch/powerpc/kvm/book3s_hv_builtin.c:kvm_hv_vm_activated"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283651260,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 13835058055283706068,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283753800,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284035544,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284139360,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284173920,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284207524,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284605112,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 13835058055284898540,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285031896,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285662660,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285694772,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 13835058055302592600,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 13835058055286003584,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 13835058055286359776,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294847468,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294863600,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/powernv-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295435852,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
  "name": "get_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
  "name": "get_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578894843,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604603404,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189151,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579197739,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071579417137,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579623533,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071579670981,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579706427,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580002466,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580020698,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580050747,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580322757,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071580518468,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580598055,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581013306,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032516,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071604811500,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071581240999,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071581490903,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585157221,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587670125,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587679141,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587685767,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587693637,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588080930,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
  "name": "get_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578888747,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604594971,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579123823,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579132731,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071579346257,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579551901,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071579599333,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579634299,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579838884,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579941138,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579961834,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579996059,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580270037,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071580466516,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580544535,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580959434,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580978596,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071604780561,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071581187671,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071581433159,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585071381,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587443997,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587452917,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587456327,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587469765,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587794498,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
  "name": "get_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578894779,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604681228,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579190223,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579198811,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071579417057,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579620813,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071579668213,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579697643,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579891574,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579994002,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580012234,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580042283,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314005,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071580509716,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580589303,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581004506,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581023716,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071604888684,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071581232199,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071581482215,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585307477,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588001277,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588010293,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588016919,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588027637,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588412706,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
  "name": "get_online_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578895339,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604681248,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579195471,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204267,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071579426113,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579654477,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071579702373,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_unregister_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579736935,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579937402,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580040738,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580066922,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580093072,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580368917,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071580566052,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580646199,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581065706,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581085732,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071604910221,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071581295735,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
      "addr": 18446744071581546967,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:disable_swap_slots_cache_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585413621,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588116717,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588125765,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588132391,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588143109,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588551298,
      "name": "get_online_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
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
void get_online_cpus()
```
</details>
</li>
</ul>
