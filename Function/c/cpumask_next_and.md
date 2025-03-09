# Function: <code>cpumask_next_and</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582945696,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:16",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/kernel/irq.c:fixup_irqs",
        "arch/x86/kernel/apic/apic.c:default_cpu_mask_to_apicid_and",
        "arch/x86/kernel/apic/vector.c:apic_retrigger_irq",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid_and",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid_and",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/watchdog.c:watchdog_park_threads",
        "kernel/watchdog.c:watchdog_unpark_threads",
        "kernel/watchdog.c:touch_all_softlockup_watchdogs",
        "lib/cpumask.c:cpumask_local_spread",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582945696,
      "name": "cpumask_next_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583232944,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:16",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:intel_cqm_cpu_starting",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/kernel/irq.c:fixup_irqs",
        "arch/x86/kernel/apic/apic.c:default_cpu_mask_to_apicid_and",
        "arch/x86/kernel/apic/vector.c:apic_retrigger_irq",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid_and",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid_and",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/watchdog.c:watchdog_unpark_threads",
        "kernel/watchdog.c:watchdog_park_threads",
        "kernel/watchdog.c:touch_all_softlockup_watchdogs",
        "lib/cpumask.c:cpumask_local_spread",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583232944,
      "name": "cpumask_next_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583348000,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:16",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:intel_cqm_cpu_starting",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/kernel/irq.c:fixup_irqs",
        "arch/x86/kernel/apic/apic.c:default_cpu_mask_to_apicid_and",
        "arch/x86/kernel/apic/vector.c:apic_retrigger_irq",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid_and",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid_and",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/watchdog.c:watchdog_unpark_threads",
        "kernel/watchdog.c:watchdog_park_threads",
        "kernel/watchdog.c:touch_all_softlockup_watchdogs",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/compaction.c:kcompactd_cpu_online",
        "lib/cpumask.c:cpumask_local_spread",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/dev.c:netif_set_xps_queue",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583348000,
      "name": "cpumask_next_and",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588199280,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:16",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/kernel/apic/vector.c:apic_retrigger_irq",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/migration.c:irq_fixup_move_pending",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/watchdog.c:watchdog_unpark_threads",
        "kernel/watchdog.c:watchdog_park_threads",
        "kernel/watchdog.c:touch_all_softlockup_watchdogs",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/compaction.c:kcompactd_cpu_online",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/dev.c:netif_set_xps_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "lib/cpumask.c:cpumask_local_spread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588199280,
      "name": "cpumask_next_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588748112,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:33",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/migration.c:irq_fixup_move_pending",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/compaction.c:kcompactd_cpu_online",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/dev.c:netif_set_xps_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "lib/cpumask.c:cpumask_local_spread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588748112,
      "name": "cpumask_next_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589126401,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:33",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/migration.c:irq_fixup_move_pending",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/dev.c:netif_set_xps_queue",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589126128,
      "name": "cpumask_next_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589361089,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:33",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/migration.c:irq_fixup_move_pending",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/powercap/idle_inject.c:idle_inject_wakeup",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589360816,
      "name": "cpumask_next_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589818144,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/migration.c:irq_fixup_move_pending",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/powercap/idle_inject.c:idle_inject_wakeup",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589817872,
      "name": "cpumask_next_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590044280,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:sched_numa_find_closest",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/migration.c:irq_fixup_move_pending",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/powercap/idle_inject.c:idle_inject_wakeup",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590044192,
      "name": "cpumask_next_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585038094,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_any_and_distribute",
        "lib/cpumask.c:cpumask_any_and_distribute",
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:wq_select_unbound_cpu",
        "kernel/workqueue.c:wq_select_unbound_cpu",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/cpupri.c:cpupri_find_fitness",
        "kernel/sched/topology.c:sched_numa_find_closest",
        "kernel/sched/topology.c:init_overlap_sched_group",
        "kernel/irq/chip.c:__irq_startup_managed",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/migration.c:irq_fixup_move_pending",
        "kernel/irq/cpuhotplug.c:migrate_one_irq",
        "kernel/irq/cpuhotplug.c:migrate_one_irq",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585038048,
      "name": "cpumask_next_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585190017,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_any_and_distribute",
        "lib/cpumask.c:cpumask_any_and_distribute",
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:wq_select_unbound_cpu",
        "kernel/workqueue.c:wq_select_unbound_cpu",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/cpupri.c:cpupri_find_fitness",
        "kernel/sched/topology.c:sched_numa_find_closest",
        "kernel/sched/topology.c:init_overlap_sched_group",
        "kernel/irq/chip.c:__irq_startup_managed",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/migration.c:irq_fixup_move_pending",
        "kernel/irq/cpuhotplug.c:migrate_one_irq",
        "kernel/irq/cpuhotplug.c:migrate_one_irq",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585189952,
      "name": "cpumask_next_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585073271,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_any_and_distribute",
        "lib/cpumask.c:cpumask_any_and_distribute",
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/cpupri.c:cpupri_find_fitness",
        "kernel/sched/topology.c:sched_numa_find_closest",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/migration.c:irq_fixup_move_pending",
        "kernel/irq/cpuhotplug.c:migrate_one_irq",
        "kernel/irq/cpuhotplug.c:migrate_one_irq",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg",
        "drivers/base/power/domain_governor.c:cpu_power_down_ok",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585073184,
      "name": "cpumask_next_and",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585519959,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_any_and_distribute",
        "lib/cpumask.c:cpumask_any_and_distribute",
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/cpupri.c:cpupri_find_fitness",
        "kernel/sched/topology.c:sched_numa_find_closest",
        "kernel/sched/topology.c:asym_cpu_capacity_scan",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/migration.c:irq_fixup_move_pending",
        "kernel/irq/cpuhotplug.c:migrate_one_irq",
        "kernel/irq/cpuhotplug.c:migrate_one_irq",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg",
        "drivers/base/power/domain_governor.c:cpu_power_down_ok",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585519872,
      "name": "cpumask_next_and",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586671958,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_any_and_distribute",
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:wq_select_unbound_cpu",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:dl_add_task_root_domain",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/base/power/domain_governor.c:cpu_power_down_ok",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586672352,
      "name": "cpumask_next_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579968178,
      "name": "cpumask_next_and",
      "external": false,
      "loc": "include/linux/cpumask.h:231",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_select_unbound_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580914575,
      "name": "cpumask_next_and",
      "external": false,
      "loc": "include/linux/cpumask.h:231",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586456298,
      "name": "cpumask_next_and",
      "external": false,
      "loc": "include/linux/cpumask.h:231",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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
  "name": "cpumask_next_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580018482,
      "name": "cpumask_next_and",
      "external": false,
      "loc": "include/linux/cpumask.h:264",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_select_unbound_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580999854,
      "name": "cpumask_next_and",
      "external": false,
      "loc": "include/linux/cpumask.h:264",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586706234,
      "name": "cpumask_next_and",
      "external": false,
      "loc": "include/linux/cpumask.h:264",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_delay_run_hw_queue"
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
  "name": "cpumask_next_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580054548,
      "name": "cpumask_next_and",
      "external": false,
      "loc": "include/linux/cpumask.h:264",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_select_unbound_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095998,
      "name": "cpumask_next_and",
      "external": false,
      "loc": "include/linux/cpumask.h:264",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586979370,
      "name": "cpumask_next_and",
      "external": false,
      "loc": "include/linux/cpumask.h:264",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_delay_run_hw_queue"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503805476,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": [
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_numa_find_closest",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/irqchip/irq-gic.c:gic_set_affinity",
        "drivers/irqchip/irq-gic-v3.c:gic_set_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate",
        "drivers/irqchip/irq-gic-v3-its.c:its_set_affinity",
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_set_affinity",
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_set_affinity",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/powercap/idle_inject.c:idle_inject_wakeup",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503805328,
      "name": "cpumask_next_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236428552,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": [
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/irqchip/irq-hip04.c:hip04_irq_set_affinity",
        "drivers/irqchip/irq-gic.c:gic_set_affinity",
        "drivers/irqchip/irq-gic-v3.c:gic_set_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate",
        "drivers/irqchip/irq-gic-v3-its.c:its_set_affinity",
        "drivers/irqchip/irq-armada-370-xp.c:armada_xp_set_affinity",
        "drivers/powercap/idle_inject.c:idle_inject_wakeup",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236428424,
      "name": "cpumask_next_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297644736,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": [
        "arch/powerpc/kernel/irq.c:irq_choose_cpu",
        "arch/powerpc/kernel/watchdog.c:watchdog_nmi_start",
        "arch/powerpc/sysdev/xics/xics-common.c:xics_get_irq_server",
        "arch/powerpc/sysdev/xive/common.c:xive_irq_set_affinity",
        "arch/powerpc/sysdev/xive/common.c:xive_pick_irq_target",
        "arch/powerpc/sysdev/xive/common.c:xive_pick_irq_target",
        "arch/powerpc/platforms/powernv/opal-imc.c:disable_nest_pmu_counters",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:sched_numa_find_closest",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/powercap/idle_inject.c:idle_inject_wakeup",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297644528,
      "name": "cpumask_next_and",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279702242,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": [
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/chip.c:irq_startup",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/irqchip/irq-sifive-plic.c:plic_set_affinity",
        "drivers/irqchip/irq-sifive-plic.c:plic_irq_unmask",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279702160,
      "name": "cpumask_next_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589646536,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:sched_numa_find_closest",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/migration.c:irq_fixup_move_pending",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589646448,
      "name": "cpumask_next_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589372408,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:sched_numa_find_closest",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/migration.c:irq_fixup_move_pending",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/time/tick-sched.c:tick_nohz_dep_set_all",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372320,
      "name": "cpumask_next_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590089912,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:sched_numa_find_closest",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/migration.c:irq_fixup_move_pending",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/powercap/idle_inject.c:idle_inject_wakeup",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590089824,
      "name": "cpumask_next_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```

```json
{
  "name": "cpumask_next_and",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590140168,
      "name": "cpumask_next_and",
      "external": true,
      "loc": "lib/cpumask.c:34",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:find_later_rq",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/topology.c:sched_numa_find_closest",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/migration.c:irq_fixup_move_pending",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/powercap/idle_inject.c:idle_inject_wakeup",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590140080,
      "name": "cpumask_next_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int cpumask_next_and(int n, const struct cpumask * src1p, const struct cpumask * src2p)
```
</details>
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
