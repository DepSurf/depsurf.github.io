# Function: <code>__cpuhp_setup_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579386400,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:1484",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386400,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 583
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579406816,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:1479",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:trace_init",
        "kernel/padata.c:padata_driver_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:setup_vmstat",
        "mm/compaction.c:kcompactd_init",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "fs/buffer.c:buffer_init",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-mq.c:blk_mq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/radix-tree.c:radix_tree_init",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "net/core/flow.c:flow_cache_hp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406816,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579395264,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:1474",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/fork.c:fork_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/padata.c:padata_driver_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "net/core/flow.c:flow_cache_hp_init",
        "lib/radix-tree.c:radix_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395264,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579423024,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:1662",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/fork.c:fork_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/padata.c:padata_driver_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "lib/radix-tree.c:radix_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579423024,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579437792,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:1744",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/fork.c:fork_init",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/padata.c:padata_driver_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmscan.c:kswapd_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "net/core/dev.c:net_dev_init",
        "lib/radix-tree.c:radix_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579437792,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579470752,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:1766",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/fork.c:fork_init",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/padata.c:padata_driver_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmscan.c:kswapd_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "net/core/dev.c:net_dev_init",
        "lib/radix-tree.c:radix_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470752,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579488560,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:1792",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/fork.c:fork_init",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/padata.c:padata_driver_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmscan.c:kswapd_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "net/core/dev.c:net_dev_init",
        "lib/radix-tree.c:radix_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488560,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579514496,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:1807",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/fork.c:fork_init",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/padata.c:padata_driver_init",
        "kernel/padata.c:padata_driver_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmscan.c:kswapd_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "net/core/dev.c:net_dev_init",
        "lib/radix-tree.c:radix_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514496,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543280,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:1938",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/vmware.c:vmware_paravirt_ops_setup",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/fork.c:fork_init",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/padata.c:padata_init",
        "kernel/padata.c:padata_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-mq.c:blk_mq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "lib/radix-tree.c:radix_tree_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "net/core/dev.c:net_dev_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543280,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579524992,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:1949",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/vmware.c:vmware_paravirt_ops_setup",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/fork.c:fork_init",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/padata.c:padata_init",
        "kernel/padata.c:padata_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "fs/io-wq.c:io_wq_init",
        "block/blk-mq.c:blk_mq_init",
        "block/blk-mq.c:blk_mq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "lib/radix-tree.c:radix_tree_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "net/core/dev.c:net_dev_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524992,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579528656,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:2052",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/fork.c:fork_init",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/padata.c:padata_init",
        "kernel/padata.c:padata_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "fs/io-wq.c:io_wq_init",
        "block/blk-mq.c:blk_mq_init",
        "block/blk-mq.c:blk_mq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "lib/radix-tree.c:radix_tree_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/iommu/iova.c:iova_cache_get",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "drivers/powercap/dtpm_cpu.c:dtpm_register_cpu",
        "net/core/dev.c:net_dev_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528656,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579600688,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:2083",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/fork.c:fork_init",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/padata.c:padata_init",
        "kernel/padata.c:padata_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/migrate.c:migrate_on_reclaim_init",
        "mm/migrate.c:migrate_on_reclaim_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "fs/io-wq.c:io_wq_init",
        "block/bio.c:init_bio",
        "block/blk-mq.c:blk_mq_init",
        "block/blk-mq.c:blk_mq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "lib/radix-tree.c:radix_tree_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/iommu/iova.c:iova_cache_get",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc",
        "drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init",
        "drivers/powercap/dtpm_cpu.c:dtpm_register_cpu",
        "net/core/dev.c:net_dev_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579600688,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579692960,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:2105",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel.c:sld_setup",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/fork.c:fork_init",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/padata.c:padata_init",
        "kernel/padata.c:padata_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/bio.c:init_bio",
        "block/blk-mq.c:blk_mq_init",
        "block/blk-mq.c:blk_mq_init",
        "block/blk-mq.c:blk_mq_init",
        "io_uring/io-wq.c:io_wq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "lib/radix-tree.c:radix_tree_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/iommu/iova.c:iova_cache_get",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc",
        "drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init",
        "net/core/dev.c:net_dev_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579692960,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579816912,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:2129",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel.c:sld_setup",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/fork.c:fork_init",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/padata.c:padata_init",
        "kernel/padata.c:padata_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/bio.c:init_bio",
        "block/blk-mq.c:blk_mq_init",
        "block/blk-mq.c:blk_mq_init",
        "block/blk-mq.c:blk_mq_init",
        "io_uring/io-wq.c:io_wq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/iommu/iova.c:iova_cache_get",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc",
        "drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init",
        "net/core/dev.c:net_dev_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "lib/radix-tree.c:radix_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816912,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579864928,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:2514",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel.c:sld_setup",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/fork.c:fork_init",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_osnoise.c:init_osnoise_tracer",
        "kernel/padata.c:padata_init",
        "kernel/padata.c:padata_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/page_alloc.c:page_alloc_init_cpuhp",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:zswap_setup",
        "mm/zswap.c:zswap_setup",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/bio.c:init_bio",
        "block/blk-mq.c:blk_mq_init",
        "block/blk-mq.c:blk_mq_init",
        "block/blk-mq.c:blk_mq_init",
        "io_uring/io-wq.c:io_wq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_register",
        "drivers/iommu/iova.c:iova_cache_get",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/net/virtio_net.c:virtio_net_driver_init",
        "drivers/net/virtio_net.c:virtio_net_driver_init",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc",
        "drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init",
        "net/core/dev.c:net_dev_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "lib/radix-tree.c:radix_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579864928,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579902832,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:2560",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel.c:sld_setup",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/fork.c:fork_init",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/time/tick-sched.c:tick_nohz_init",
        "kernel/crash_core.c:crash_hotplug_init",
        "kernel/trace/trace_hwlat.c:init_hwlat_tracer",
        "kernel/trace/trace_osnoise.c:init_osnoise_tracer",
        "kernel/padata.c:padata_init",
        "kernel/padata.c:padata_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/page_alloc.c:page_alloc_init_cpuhp",
        "mm/slub.c:kmem_cache_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:zswap_setup",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/bio.c:init_bio",
        "block/blk-mq.c:blk_mq_init",
        "block/blk-mq.c:blk_mq_init",
        "block/blk-mq.c:blk_mq_init",
        "io_uring/io-wq.c:io_wq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_register",
        "drivers/iommu/iova.c:iova_cache_get",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/net/virtio_net.c:virtio_net_driver_init",
        "drivers/net/virtio_net.c:virtio_net_driver_init",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc",
        "drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init",
        "net/core/dev.c:net_dev_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "lib/radix-tree.c:radix_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902832,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490651120,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:1807",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/debug-monitors.c:debug_monitors_init",
        "arch/arm64/kernel/fpsimd.c:fpsimd_init",
        "arch/arm64/kernel/cpuinfo.c:cpuinfo_regs_init",
        "arch/arm64/kernel/hw_breakpoint.c:arch_hw_breakpoint_init",
        "arch/arm64/kernel/armv8_deprecated.c:armv8_deprecated_init",
        "virt/kvm/kvm_main.c:kvm_init",
        "virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_hyp_init",
        "virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init",
        "arch/arm/xen/enlighten.c:xen_guest_init",
        "kernel/fork.c:fork_init",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/padata.c:padata_driver_init",
        "kernel/padata.c:padata_driver_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmscan.c:kswapd_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_l1_intc_of_init",
        "drivers/irqchip/irq-gic.c:__gic_init_bases",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/soc/fsl/qbman/bman_portal.c:bman_portal_driver_init",
        "drivers/soc/fsl/qbman/qman_portal.c:qman_portal_driver_init",
        "drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/firmware/arm_sdei.c:sdei_probe",
        "drivers/firmware/arm_sdei.c:sdei_device_thaw",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_register",
        "drivers/clocksource/dummy_timer.c:dummy_timer_register",
        "drivers/perf/arm-cci.c:cci_pmu_probe",
        "drivers/perf/arm-ccn.c:arm_ccn_init",
        "drivers/perf/arm_pmu.c:arm_pmu_hp_init",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_module_init",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_module_init",
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_module_init",
        "drivers/perf/qcom_l2_pmu.c:register_l2_cache_pmu_driver",
        "drivers/perf/qcom_l3_pmu.c:register_qcom_l3_cache_pmu_driver",
        "net/core/dev.c:net_dev_init",
        "lib/radix-tree.c:radix_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490651120,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224727636,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:1807",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/vfp/vfpmodule.c:vfp_init",
        "arch/arm/kernel/smp_twd.c:twd_local_timer_of_register",
        "arch/arm/mm/cache-l2x0.c:l2c310_enable",
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_init",
        "arch/arm/common/bL_switcher.c:bL_switcher_init",
        "arch/arm/common/bL_switcher.c:bL_switcher_init",
        "arch/arm/mach-mvebu/coherency.c:coherency_init",
        "arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_prepare_cpus",
        "arch/arm/mach-imx/mmdc.c:imx_mmdc_probe",
        "arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init",
        "arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init",
        "arch/arm/mach-shmobile/platsmp-scu.c:shmobile_smp_scu_prepare_cpus",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/padata.c:padata_driver_init",
        "kernel/padata.c:padata_driver_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmscan.c:kswapd_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/irqchip/irq-hip04.c:hip04_of_init",
        "drivers/irqchip/irq-gic.c:__gic_init_bases",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/cpuidle/coupled.c:cpuidle_coupled_init",
        "drivers/cpuidle/coupled.c:cpuidle_coupled_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init",
        "drivers/clocksource/timer-tegra.c:tegra_init_timer",
        "drivers/clocksource/exynos_mct.c:mct_init_dt",
        "drivers/clocksource/timer-qcom.c:msm_dt_timer_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_of_init",
        "drivers/clocksource/arm_global_timer.c:global_timer_of_register",
        "drivers/clocksource/dummy_timer.c:dummy_timer_register",
        "drivers/perf/arm-cci.c:cci_pmu_probe",
        "drivers/perf/arm-ccn.c:arm_ccn_init",
        "drivers/perf/arm_pmu.c:arm_pmu_hp_init",
        "net/core/dev.c:net_dev_init",
        "lib/radix-tree.c:radix_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224727636,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283472736,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:1807",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/sysfs.c:topology_init",
        "arch/powerpc/kernel/watchdog.c:watchdog_nmi_probe",
        "arch/powerpc/mm/numa.c:initmem_init",
        "arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write",
        "arch/powerpc/perf/core-book3s.c:register_power_pmu",
        "arch/powerpc/perf/imc-pmu.c:init_imc_pmu",
        "arch/powerpc/perf/imc-pmu.c:init_imc_pmu",
        "arch/powerpc/perf/imc-pmu.c:init_imc_pmu",
        "arch/powerpc/perf/imc-pmu.c:init_imc_pmu",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/padata.c:padata_driver_init",
        "kernel/padata.c:padata_driver_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmscan.c:kswapd_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/cpuidle/cpuidle-pseries.c:pseries_processor_idle_init",
        "drivers/cpuidle/cpuidle-pseries.c:pseries_processor_idle_init",
        "drivers/cpuidle/cpuidle-powernv.c:powernv_processor_idle_init",
        "drivers/cpuidle/cpuidle-powernv.c:powernv_processor_idle_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/clocksource/dummy_timer.c:dummy_timer_register",
        "net/core/dev.c:net_dev_init",
        "lib/radix-tree.c:radix_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283472736,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271399588,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:1807",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmscan.c:kswapd_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/clocksource/timer-riscv.c:riscv_timer_init_dt",
        "net/core/dev.c:net_dev_init",
        "lib/radix-tree.c:radix_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271399588,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579488160,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:1807",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/fork.c:fork_init",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/padata.c:padata_driver_init",
        "kernel/padata.c:padata_driver_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmscan.c:kswapd_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "net/core/dev.c:net_dev_init",
        "lib/radix-tree.c:radix_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488160,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579417040,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:1807",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/fork.c:fork_init",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/time/tick-sched.c:tick_nohz_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/padata.c:padata_driver_init",
        "kernel/padata.c:padata_driver_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmscan.c:kswapd_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "drivers/hv/vmbus_drv.c:hv_acpi_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "net/core/dev.c:net_dev_init",
        "lib/radix-tree.c:radix_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417040,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579488080,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:1807",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/fork.c:fork_init",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/padata.c:padata_driver_init",
        "kernel/padata.c:padata_driver_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmscan.c:kswapd_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "net/core/dev.c:net_dev_init",
        "lib/radix-tree.c:radix_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488080,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "__cpuhp_setup_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579520304,
      "name": "__cpuhp_setup_state",
      "external": true,
      "loc": "kernel/cpu.c:1807",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/xen/enlighten.c:xen_cpuhp_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/hpet.c:hpet_late_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/fork.c:fork_init",
        "kernel/softirq.c:spawn_ksoftirqd",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/padata.c:padata_driver_init",
        "kernel/padata.c:padata_driver_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmscan.c:kswapd_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:init_mm_internals",
        "mm/compaction.c:kcompactd_init",
        "mm/page_alloc.c:page_alloc_init",
        "mm/swap_slots.c:enable_swap_slots_cache",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/zsmalloc.c:zs_init",
        "fs/buffer.c:buffer_init",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/acpi/processor_driver.c:acpi_processor_driver_init",
        "drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "net/core/dev.c:net_dev_init",
        "lib/radix-tree.c:radix_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520304,
      "name": "__cpuhp_setup_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int __cpuhp_setup_state(enum cpuhp_state state, const char * name, bool invoke, int (*)(unsigned int) startup, int (*)(unsigned int) teardown)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool multi_instance</code>
</li>
</ul>
</details>
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
