# Function: <code>kmem_cache_alloc_node_trace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580856736,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:2610",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/intel/core.c:allocate_shared_regs",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/rapl.c:rapl_cpu_prepare",
        "arch/x86/kernel/apic/vector.c:alloc_apic_chip_data",
        "arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node",
        "kernel/workqueue.c:alloc_worker",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/callchain.c:get_callchain_buffers",
        "mm/mempool.c:mempool_create_node",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/vmalloc.c:vm_map_ram",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/noop-iosched.c:noop_init_queue",
        "block/deadline-iosched.c:deadline_init_queue",
        "block/cfq-iosched.c:cfq_init_queue",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "lib/genalloc.c:gen_pool_create",
        "drivers/scsi/scsi_lib.c:scsi_init_request",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "net/core/dev.c:netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856736,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580988976,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:2739",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare",
        "arch/x86/events/intel/core.c:allocate_shared_regs",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/kernel/apic/vector.c:alloc_apic_chip_data",
        "arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_worker",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/core.c:perf_event_set_addr_filter",
        "mm/mempool.c:mempool_create_node",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/vmalloc.c:vm_map_ram",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/noop-iosched.c:noop_init_queue",
        "block/deadline-iosched.c:deadline_init_queue",
        "block/cfq-iosched.c:cfq_init_queue",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "lib/genalloc.c:gen_pool_create",
        "drivers/char/random.c:rand_initialize",
        "drivers/scsi/scsi_lib.c:scsi_init_request",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "net/core/dev.c:netif_set_xps_queue",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580988976,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581062752,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:2761",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare",
        "arch/x86/events/intel/core.c:allocate_shared_regs",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu",
        "arch/x86/kernel/apic/vector.c:alloc_apic_chip_data",
        "arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_worker",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/core.c:perf_event_set_addr_filter",
        "mm/mempool.c:mempool_create_node",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/vmalloc.c:vm_map_ram",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/noop-iosched.c:noop_init_queue",
        "block/deadline-iosched.c:deadline_init_queue",
        "block/cfq-iosched.c:cfq_init_queue",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "lib/genalloc.c:gen_pool_create",
        "drivers/char/random.c:rand_initialize",
        "drivers/lightnvm/core.c:nvm_alloc_dev",
        "drivers/scsi/scsi_lib.c:scsi_init_request",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "net/core/dev.c:netif_set_xps_queue",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581062752,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581106848,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:2758",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare",
        "arch/x86/events/intel/core.c:allocate_shared_regs",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu",
        "arch/x86/kernel/apic/vector.c:alloc_apic_chip_data",
        "arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_worker",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_swevent_init_cpu",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "mm/mempool.c:mempool_create_node",
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/vmalloc.c:vm_map_ram",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/noop-iosched.c:noop_init_queue",
        "block/deadline-iosched.c:deadline_init_queue",
        "block/cfq-iosched.c:cfq_init_queue",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "lib/genalloc.c:gen_pool_create",
        "drivers/char/random.c:rand_initialize",
        "drivers/lightnvm/core.c:nvm_alloc_dev",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "net/core/dev.c:netif_set_xps_queue",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581106848,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581222672,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:2771",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare",
        "arch/x86/events/intel/core.c:allocate_shared_regs",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_worker",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/devmap.c:dev_map_update_elem",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/events/core.c:perf_swevent_init_cpu",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "mm/mempool.c:mempool_create_node",
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/vmalloc.c:vm_map_ram",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/noop-iosched.c:noop_init_queue",
        "block/deadline-iosched.c:deadline_init_queue",
        "block/cfq-iosched.c:cfq_init_queue",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "lib/genalloc.c:gen_pool_create",
        "drivers/char/random.c:rand_initialize",
        "drivers/lightnvm/core.c:nvm_alloc_dev",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "net/core/dev.c:netif_set_xps_queue",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581222672,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581363280,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:2754",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare",
        "arch/x86/events/intel/core.c:allocate_shared_regs",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_worker",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/devmap.c:dev_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/events/core.c:perf_swevent_init_cpu",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "mm/mempool.c:mempool_create_node",
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/vmalloc.c:vm_map_ram",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/noop-iosched.c:noop_init_queue",
        "block/deadline-iosched.c:deadline_init_queue",
        "block/cfq-iosched.c:cfq_init_queue",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "lib/genalloc.c:gen_pool_create",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/lightnvm/core.c:nvm_alloc_dev",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "net/core/dev.c:netif_set_xps_queue",
        "net/core/page_pool.c:page_pool_create",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581363280,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581448544,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:2804",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_alloc",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_worker",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/devmap.c:dev_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/events/core.c:perf_swevent_init_cpu",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "mm/mempool.c:mempool_create_node",
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/vmalloc.c:vm_map_ram",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/mq-deadline.c:dd_init_queue",
        "lib/genalloc.c:gen_pool_create",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/lightnvm/core.c:nvm_alloc_dev",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "net/core/page_pool.c:page_pool_create",
        "net/core/skmsg.c:sk_psock_init",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448544,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581561872,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:2816",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_alloc",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_worker",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/devmap.c:dev_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/core.c:perf_event_set_filter",
        "mm/mempool.c:mempool_create_node",
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/vmalloc.c:vm_map_ram",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/mq-deadline.c:dd_init_queue",
        "lib/genalloc.c:gen_pool_create",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/lightnvm/core.c:nvm_alloc_dev",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "net/core/page_pool.c:page_pool_create",
        "net/core/skmsg.c:sk_psock_init",
        "net/ipv4/tcp.c:__tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561872,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581626896,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:2812",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_alloc",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_worker",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/core.c:perf_event_set_filter",
        "mm/mempool.c:mempool_create_node",
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/vmalloc.c:vm_map_ram",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/mq-deadline.c:dd_init_queue",
        "lib/genalloc.c:gen_pool_create",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/lightnvm/core.c:nvm_alloc_dev",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "net/core/page_pool.c:page_pool_create",
        "net/core/skmsg.c:sk_psock_init",
        "net/ipv4/tcp.c:__tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581626896,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581843856,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:2870",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_alloc_nb",
        "arch/x86/events/amd/uncore.c:amd_uncore_alloc",
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
        "arch/x86/platform/uv/tlb_uv.c:pq_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:create_worker",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/events/core.c:perf_swevent_init_cpu",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "mm/mempool.c:mempool_create",
        "mm/backing-dev.c:bdi_alloc",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:alloc_mem_cgroup_per_node_info",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:create_io_worker",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/mq-deadline.c:dd_init_queue",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/lightnvm/core.c:nvm_alloc_dev",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "net/core/page_pool.c:page_pool_create",
        "net/core/skmsg.c:sk_psock_init",
        "net/ipv4/tcp.c:__tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581843856,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581894464,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:2938",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_alloc_nb",
        "arch/x86/events/amd/uncore.c:amd_uncore_alloc",
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
        "kernel/workqueue.c:create_worker",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/events/core.c:perf_swevent_init_cpu",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "mm/mempool.c:mempool_create",
        "mm/backing-dev.c:bdi_alloc",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:alloc_mem_cgroup_per_node_info",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:create_io_worker",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:__alloc_disk_node",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/mq-deadline.c:dd_init_queue",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/lightnvm/core.c:nvm_alloc_dev",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "net/core/page_pool.c:page_pool_create",
        "net/core/skmsg.c:sk_psock_init",
        "net/ipv4/tcp.c:__tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581894464,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581924720,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:2960",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_alloc",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:alloc_worker",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "mm/mempool.c:mempool_create",
        "mm/backing-dev.c:bdi_alloc",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:create_io_worker",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:__alloc_disk_node",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/mq-deadline.c:dd_init_queue",
        "lib/sbitmap.c:sbitmap_queue_init_node",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/lightnvm/core.c:nvm_alloc_dev",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "net/core/page_pool.c:page_pool_create",
        "net/core/skmsg.c:sk_psock_init",
        "net/ipv4/tcp.c:__tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581924720,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582227648,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:3259",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:alloc_worker",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "mm/mempool.c:mempool_create",
        "mm/backing-dev.c:bdi_alloc",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:create_io_worker",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:__alloc_disk_node",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/mq-deadline.c:dd_init_sched",
        "lib/sbitmap.c:sbitmap_queue_init_node",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "net/core/page_pool.c:page_pool_create",
        "net/core/skmsg.c:sk_psock_init",
        "net/ipv4/tcp.c:__tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582227648,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 741
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
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582685776,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:3303",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
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
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "net/core/page_pool.c:page_pool_create",
        "net/core/skmsg.c:sk_psock_init",
        "net/ipv4/tcp.c:__tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582685776,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493073936,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:2812",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_worker",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/core.c:perf_event_set_filter",
        "mm/mempool.c:mempool_create_node",
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/vmalloc.c:vm_map_ram",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/mq-deadline.c:dd_init_queue",
        "lib/genalloc.c:gen_pool_create",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/lightnvm/core.c:nvm_alloc_dev",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "net/core/page_pool.c:page_pool_create",
        "net/core/skmsg.c:sk_psock_init",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493073936,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224850664,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 3224891788,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225006324,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ],
      "caller_func": []
    },
    {
      "addr": 3225021144,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/rt.c:alloc_rt_sched_group"
      ],
      "caller_func": []
    },
    {
      "addr": 3225060036,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 3225195384,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 3225234972,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 3225729424,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 3225777096,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226142268,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226167880,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 3226172720,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 3226277836,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/core.c:perf_event_set_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226347060,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226485032,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 3226648636,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/vmalloc.c:vm_map_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226735432,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_dstmem_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3226741992,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3243459120,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229135232,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/elevator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/elevator.c:elevator_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3229171668,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:blk_alloc_flush_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3229213196,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ],
      "caller_func": []
    },
    {
      "addr": 3229222532,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_init_tags"
      ],
      "caller_func": []
    },
    {
      "addr": 3229248832,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:__alloc_disk_node"
      ],
      "caller_func": []
    },
    {
      "addr": 3229254688,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:add_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229317332,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3229342116,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229368132,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/mq-deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_init_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229525076,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3229688332,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231505736,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_alloc_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 3233082564,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3233680404,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device"
      ],
      "caller_func": []
    },
    {
      "addr": 3233731580,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "drivers/md/dm-rq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235007928,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3235013720,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235375132,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "net/ipv6/seg6_hmac.c",
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
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286517024,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:2812",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/sysdev/xive/common.c:xive_prepare_cpu",
        "arch/powerpc/platforms/powernv/pci.c:pnv_pci_table_alloc",
        "arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_pci_link_table_and_group",
        "arch/powerpc/platforms/pseries/iommu.c:iommu_pseries_alloc_group",
        "arch/powerpc/platforms/pseries/iommu.c:iommu_pseries_alloc_group",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_worker",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/taskstats.c:add_del_listener",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/core.c:perf_event_set_filter",
        "mm/mempool.c:mempool_create_node",
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/vmalloc.c:vm_map_ram",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/mq-deadline.c:dd_init_queue",
        "lib/genalloc.c:gen_pool_create",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/lightnvm/core.c:nvm_alloc_dev",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "net/core/page_pool.c:page_pool_create",
        "net/core/skmsg.c:sk_psock_init",
        "net/ipv4/tcp.c:__tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286517024,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271491650,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271527732,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271607704,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271620580,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/rt.c:alloc_rt_sched_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271649408,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271721662,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271756726,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272097614,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272137258,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272392022,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272414398,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272419098,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272501100,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/core.c:perf_event_set_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272540528,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272658578,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272796340,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vm_map_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272866522,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_dstmem_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272872820,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279791172,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_index_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270701898,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274927794,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/elevator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/elevator.c:elevator_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274956920,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:blk_alloc_flush_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274999590,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_init_tags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275021062,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:__alloc_disk_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275026214,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:add_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275074476,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275096986,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275116382,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/mq-deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_init_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275253158,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275400880,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276321320,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_alloc_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277490224,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277877880,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277922352,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "drivers/md/dm-rq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278502092,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278508308,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278808884,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmem_cache_alloc_node_trace",
      "external": false,
      "loc": "include/linux/slab.h:440",
      "file": "net/ipv6/seg6_hmac.c",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581595632,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:2812",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_alloc",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_worker",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/core.c:perf_event_set_filter",
        "mm/mempool.c:mempool_create_node",
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/vmalloc.c:vm_map_ram",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/mq-deadline.c:dd_init_queue",
        "lib/genalloc.c:gen_pool_create",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/lightnvm/core.c:nvm_alloc_dev",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/pci.c:nvme_probe",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "net/core/page_pool.c:page_pool_create",
        "net/core/skmsg.c:sk_psock_init",
        "net/ipv4/tcp.c:__tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595632,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581537040,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:2812",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_alloc",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_worker",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/core.c:perf_event_set_filter",
        "mm/mempool.c:mempool_create_node",
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/vmalloc.c:vm_map_ram",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/mq-deadline.c:dd_init_queue",
        "lib/genalloc.c:gen_pool_create",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/pci.c:nvme_probe",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "net/core/page_pool.c:page_pool_create",
        "net/core/skmsg.c:sk_psock_init",
        "net/ipv4/tcp.c:__tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581537040,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581586944,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:2812",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_alloc",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_worker",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/core.c:perf_event_set_filter",
        "mm/mempool.c:mempool_create_node",
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/vmalloc.c:vm_map_ram",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/mq-deadline.c:dd_init_queue",
        "lib/genalloc.c:gen_pool_create",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/lightnvm/core.c:nvm_alloc_dev",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "net/core/page_pool.c:page_pool_create",
        "net/core/skmsg.c:sk_psock_init",
        "net/ipv4/tcp.c:__tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586944,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```

```json
{
  "name": "kmem_cache_alloc_node_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652192,
      "name": "kmem_cache_alloc_node_trace",
      "external": true,
      "loc": "mm/slub.c:2812",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_cpu_prepare",
        "arch/x86/events/amd/uncore.c:amd_uncore_alloc",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/core.c:intel_cpuc_prepare",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_worker",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_map_alloc",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/core.c:perf_event_set_filter",
        "mm/mempool.c:mempool_create_node",
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/vmalloc.c:vm_map_ram",
        "mm/zswap.c:zswap_dstmem_prepare",
        "mm/dmapool.c:dma_pool_create",
        "mm/sparse.c:sparse_index_alloc",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq-tag.c:blk_mq_init_tags",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/mq-deadline.c:dd_init_queue",
        "lib/genalloc.c:gen_pool_create",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/lightnvm/core.c:nvm_alloc_dev",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_table_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "net/core/page_pool.c:page_pool_create",
        "net/core/skmsg.c:sk_psock_init",
        "net/ipv4/tcp.c:__tcp_alloc_md5sig_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652192,
      "name": "kmem_cache_alloc_node_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 599
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
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * kmem_cache_alloc_node_trace(struct kmem_cache * s, gfp_t gfpflags, int node, size_t size)
```
</details>
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
