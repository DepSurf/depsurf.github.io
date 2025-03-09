# Function: <code>_find_first_and_bit</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int _find_first_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size)
```

```json
{
  "name": "_find_first_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586083856,
      "name": "_find_first_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:96",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:wq_select_unbound_cpu",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_utility.c:housekeeping_any_cpu",
        "kernel/sched/build_utility.c:sched_numa_find_closest",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/migration.c:irq_fixup_move_pending",
        "kernel/irq/cpuhotplug.c:migrate_one_irq",
        "kernel/irq/cpuhotplug.c:irq_needs_fixup",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "lib/cpumask.c:cpumask_any_and_distribute",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586083856,
      "name": "_find_first_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
long unsigned int _find_first_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size)
```

```json
{
  "name": "_find_first_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587065024,
      "name": "_find_first_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:110",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:wq_select_unbound_cpu",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_utility.c:housekeeping_any_cpu",
        "kernel/sched/build_utility.c:sched_numa_find_closest",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/migration.c:irq_fixup_move_pending",
        "kernel/irq/cpuhotplug.c:migrate_one_irq",
        "kernel/irq/cpuhotplug.c:irq_needs_fixup",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "lib/cpumask.c:cpumask_any_and_distribute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587065024,
      "name": "_find_first_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
long unsigned int _find_first_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size)
```

```json
{
  "name": "_find_first_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587323088,
      "name": "_find_first_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:110",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:wq_select_unbound_cpu",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_utility.c:sched_numa_find_closest",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/migration.c:irq_fixup_move_pending",
        "kernel/irq/cpuhotplug.c:migrate_one_irq",
        "kernel/irq/cpuhotplug.c:irq_needs_fixup",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/bpf/cpumask.c:bpf_cpumask_first_and",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "lib/cpumask.c:cpumask_any_and_distribute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587323088,
      "name": "_find_first_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
long unsigned int _find_first_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size)
```

```json
{
  "name": "_find_first_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587606032,
      "name": "_find_first_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:110",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:wq_select_unbound_cpu",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_utility.c:sched_numa_find_closest",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/migration.c:irq_fixup_move_pending",
        "kernel/irq/cpuhotplug.c:migrate_one_irq",
        "kernel/irq/cpuhotplug.c:irq_needs_fixup",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_any",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/bpf/cpumask.c:bpf_cpumask_first_and",
        "mm/compaction.c:kcompactd_cpu_online",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "lib/cpumask.c:cpumask_any_and_distribute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587606032,
      "name": "_find_first_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
long unsigned int _find_first_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size)
```
</details>
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
