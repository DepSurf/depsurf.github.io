# Function: <code>kmalloc_node_trace</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void * kmalloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmalloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582652528,
      "name": "kmalloc_node_trace",
      "external": true,
      "loc": "mm/slab_common.c:1072",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer",
        "arch/x86/events/intel/pt.c:pt_addr_filters_init",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:alloc_worker",
        "kernel/smpboot.c:__smpboot_create_thread",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "mm/mempool.c:mempool_create",
        "mm/backing-dev.c:bdi_alloc",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:__alloc_disk_node",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/mq-deadline.c:dd_init_sched",
        "io_uring/io-wq.c:io_wq_create",
        "io_uring/io-wq.c:create_io_worker",
        "lib/sbitmap.c:sbitmap_queue_init_node",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-table.c:dm_table_alloc_md_mempools",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "net/core/page_pool.c:page_pool_create",
        "net/core/skmsg.c:sk_psock_init",
        "net/ipv4/tcp.c:__tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582652528,
      "name": "kmalloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void * kmalloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmalloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582862048,
      "name": "kmalloc_node_trace",
      "external": true,
      "loc": "mm/slab_common.c:1086",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer",
        "arch/x86/events/intel/pt.c:pt_addr_filters_init",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_cluster.c:alloc_clustermask",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:alloc_worker",
        "kernel/smpboot.c:__smpboot_create_thread",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "mm/mempool.c:mempool_create",
        "mm/backing-dev.c:bdi_alloc",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:__alloc_disk_node",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/mq-deadline.c:dd_init_sched",
        "lib/sbitmap.c:sbitmap_queue_init_node",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-table.c:dm_table_alloc_md_mempools",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "net/core/page_pool.c:page_pool_create",
        "net/core/skmsg.c:sk_psock_init",
        "net/ipv4/tcp.c:__tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582862048,
      "name": "kmalloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void * kmalloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmalloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583413568,
      "name": "kmalloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:4017",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer",
        "arch/x86/events/intel/pt.c:pt_addr_filters_init",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_cluster.c:alloc_clustermask",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:alloc_worker",
        "kernel/smpboot.c:__smpboot_create_thread",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "mm/mempool.c:mempool_create",
        "mm/shrinker.c:expand_one_shrinker_info",
        "mm/shrinker.c:alloc_shrinker_info",
        "mm/backing-dev.c:bdi_alloc",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:__alloc_disk_node",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/mq-deadline.c:dd_init_sched",
        "lib/genalloc.c:gen_pool_create",
        "lib/sbitmap.c:sbitmap_queue_init_node",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_interrupter",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-table.c:dm_table_alloc_md_mempools",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "net/core/page_pool.c:page_pool_create",
        "net/core/skmsg.c:sk_psock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583413568,
      "name": "kmalloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 897
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void * kmalloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
