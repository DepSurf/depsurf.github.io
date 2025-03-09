# Function: <code>register_cpu_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int register_cpu_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_cpu_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579374128,
      "name": "register_cpu_notifier",
      "external": true,
      "loc": "kernel/cpu.c:196",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/cpu.c:smpboot_thread_init",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "kernel/smp.c:call_function_init",
        "kernel/relay.c:relay_init",
        "kernel/padata.c:padata_alloc",
        "mm/page_alloc.c:page_alloc_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmscan.c:kswapd_init",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "fs/buffer.c:buffer_init",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-iopoll.c:blk_iopoll_setup",
        "block/blk-mq.c:blk_mq_init",
        "block/blk-mq-cpu.c:blk_mq_cpu_init",
        "lib/radix-tree.c:radix_tree_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init",
        "drivers/net/virtio_net.c:virtnet_restore",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374128,
      "name": "register_cpu_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int register_cpu_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_cpu_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579383728,
      "name": "register_cpu_notifier",
      "external": true,
      "loc": "kernel/cpu.c:273",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "kernel/printk/printk.c:printk_late_init",
        "kernel/relay.c:relay_init",
        "kernel/padata.c:padata_alloc",
        "mm/page_alloc.c:page_alloc_init",
        "mm/page-writeback.c:page_writeback_init",
        "mm/vmscan.c:kswapd_init",
        "mm/compaction.c:kcompactd_init",
        "mm/slub.c:kmem_cache_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "fs/buffer.c:buffer_init",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-mq.c:blk_mq_init",
        "block/blk-mq-cpu.c:blk_mq_cpu_init",
        "lib/radix-tree.c:radix_tree_init",
        "lib/percpu_counter.c:percpu_counter_startup",
        "lib/irq_poll.c:irq_poll_setup",
        "drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/net/virtio_net.c:virtnet_restore",
        "drivers/net/virtio_net.c:virtnet_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383728,
      "name": "register_cpu_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int register_cpu_notifier(struct notifier_block * nb)
```
</details>
</li>
</ul>
