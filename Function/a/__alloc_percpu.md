# Function: <code>__alloc_percpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580620400,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1080",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/events/intel/uncore.c:uncore_types_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/cpuacct.c:cpuacct_css_alloc",
        "kernel/sched/cpuacct.c:cpuacct_css_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/rcu/srcu.c:init_srcu_struct",
        "kernel/smp.c:hotplug_cfd",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/trace/trace.c:allocate_trace_buffer",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_event_perf.c:perf_trace_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:SyS_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:SyS_io_setup",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/genhd.c:alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "lib/percpu_ida.c:__percpu_ida_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/md/dm-stats.c:dm_stats_init",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/flow.c:flow_cache_init",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_hash_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/icmp.c:icmp_sk_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580620400,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580723152,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1073",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/cpuacct.c:cpuacct_css_alloc",
        "kernel/sched/cpuacct.c:cpuacct_css_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/rcu/srcu.c:init_srcu_struct",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/trace/trace.c:allocate_trace_buffer",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_event_perf.c:perf_trace_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init",
        "kernel/trace/trace_kprobe.c:create_trace_kprobe",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:SyS_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:SyS_io_setup",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/genhd.c:alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "lib/percpu_ida.c:__percpu_ida_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/md/dm-stats.c:dm_stats_init",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/flow.c:flow_cache_init",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_hash_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/icmp.c:icmp_sk_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580723152,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580788976,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1077",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/cpuacct.c:cpuacct_css_alloc",
        "kernel/sched/cpuacct.c:cpuacct_css_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/rcu/srcu.c:init_srcu_struct",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/relay.c:relay_open",
        "kernel/trace/trace.c:allocate_trace_buffer",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_event_perf.c:perf_trace_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init",
        "kernel/trace/trace_kprobe.c:create_trace_kprobe",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:SyS_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "crypto/scompress.c:crypto_scomp_alloc_scratches",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/genhd.c:alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "lib/percpu_ida.c:__percpu_ida_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/md/dm-stats.c:dm_stats_init",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/flow.c:flow_cache_init",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_hash_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/icmp.c:icmp_sk_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580788976,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580827664,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1077",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/relay.c:relay_open",
        "kernel/trace/trace.c:allocate_trace_buffer",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_event_perf.c:perf_trace_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init",
        "kernel/trace/trace_kprobe.c:create_trace_kprobe",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:SyS_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:__kmem_cache_create",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "crypto/scompress.c:crypto_scomp_alloc_scratches",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/genhd.c:alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-throttle.c:blk_throtl_init",
        "lib/percpu_ida.c:__percpu_ida_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm-stats.c:dm_stats_init",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/flow.c:flow_cache_init",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_hash_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580827664,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580920400,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1537",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/hyperv/mmu.c:hyper_alloc_mmu",
        "arch/x86/hyperv/mmu.c:hyper_alloc_mmu",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/matrix.c:irq_alloc_matrix",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/stat.c:cgroup_stat_init",
        "kernel/relay.c:relay_open",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_event_perf.c:perf_trace_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init",
        "kernel/trace/trace_kprobe.c:create_trace_kprobe",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:SYSC_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:__kmem_cache_create",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "crypto/scompress.c:crypto_scomp_alloc_scratches",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-throttle.c:blk_throtl_init",
        "lib/percpu_ida.c:__percpu_ida_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm-stats.c:dm_stats_init",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920400,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581054528,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1546",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/matrix.c:irq_alloc_matrix",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "crypto/scompress.c:crypto_scomp_alloc_scratches",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "lib/percpu_ida.c:__percpu_ida_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm-stats.c:dm_stats_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581054528,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581132320,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1557",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/psi.c:psi_cgroup_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/matrix.c:irq_alloc_matrix",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "crypto/scompress.c:crypto_scomp_alloc_scratches",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm-stats.c:dm_stats_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581132320,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581200016,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1794",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/psi.c:psi_cgroup_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/matrix.c:irq_alloc_matrix",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/iova.c:init_iova_flush_queue",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm-stats.c:dm_stats_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581200016,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581258480,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1794",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/psi.c:psi_cgroup_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/matrix.c:irq_alloc_matrix",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-iocost.c:blk_iocost_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/iova.c:init_iova_flush_queue",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm-stats.c:dm_stats_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581258480,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581447728,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1771",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/psi.c:psi_cgroup_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/matrix.c:irq_alloc_matrix",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/trace/trace.c:allocate_trace_buffer",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_event_perf.c:perf_trace_event_reg",
        "kernel/trace/trace_event_perf.c:perf_trace_event_reg",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:uprobe_buffer_init",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:alloc_mem_cgroup_per_node_info",
        "mm/memcontrol.c:alloc_mem_cgroup_per_node_info",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:add_partition",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-iocost.c:blk_iocost_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/iova.c:init_iova_rcaches",
        "drivers/iommu/iova.c:init_iova_flush_queue",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm-stats.c:dm_stats_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/af_inet6.c:ipv6_init_mibs",
        "net/ipv6/af_inet6.c:ipv6_init_mibs",
        "net/ipv6/af_inet6.c:ipv6_init_mibs",
        "net/ipv6/af_inet6.c:ipv6_init_mibs",
        "net/ipv6/addrconf.c:snmp6_alloc_dev",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "net/packet/af_packet.c:packet_create",
        "net/mptcp/mib.c:mptcp_mib_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581447728,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581491552,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1904",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/psi.c:psi_cgroup_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/matrix.c:irq_alloc_matrix",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/trace/trace.c:allocate_trace_buffer",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_event_perf.c:perf_trace_event_reg",
        "kernel/trace/trace_event_perf.c:perf_trace_event_reg",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:uprobe_buffer_init",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/devmap.c:dev_map_notification",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/shmem.c:shmem_fill_super",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/block_dev.c:bdev_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-iocost.c:blk_iocost_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/iova.c:init_iova_rcaches",
        "drivers/iommu/iova.c:init_iova_flush_queue",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm-stats.c:dm_stats_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/af_inet6.c:ipv6_init_mibs",
        "net/ipv6/af_inet6.c:ipv6_init_mibs",
        "net/ipv6/af_inet6.c:ipv6_init_mibs",
        "net/ipv6/af_inet6.c:ipv6_init_mibs",
        "net/ipv6/addrconf.c:snmp6_alloc_dev",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "net/packet/af_packet.c:packet_create",
        "net/mptcp/mib.c:mptcp_mib_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581491552,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581510976,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1905",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/psi.c:psi_cgroup_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/matrix.c:irq_alloc_matrix",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/trace/trace.c:allocate_trace_buffer",
        "kernel/trace/trace_functions.c:func_set_flag",
        "kernel/trace/trace_functions.c:function_trace_init",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/devmap.c:dev_map_notification",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/shmem.c:shmem_fill_super",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/block_dev.c:bdev_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-iocost.c:blk_iocost_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/iova.c:init_iova_flush_queue",
        "drivers/iommu/iova.c:init_iova_domain",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm-stats.c:dm_stats_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/af_inet6.c:inet6_net_init",
        "net/ipv6/af_inet6.c:inet6_net_init",
        "net/ipv6/af_inet6.c:inet6_net_init",
        "net/ipv6/af_inet6.c:inet6_net_init",
        "net/ipv6/addrconf.c:ipv6_add_dev",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "net/packet/af_packet.c:packet_create",
        "net/mptcp/mib.c:mptcp_mib_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510976,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581774080,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1948",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/psi.c:psi_cgroup_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/matrix.c:irq_alloc_matrix",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/trace/trace.c:allocate_trace_buffer",
        "kernel/trace/trace_functions.c:func_set_flag",
        "kernel/trace/trace_functions.c:function_trace_init",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/devmap.c:dev_map_notification",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/shmem.c:shmem_fill_super",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "block/bdev.c:bdev_alloc",
        "block/bio.c:bioset_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-iocost.c:blk_iocost_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/iova.c:init_iova_flush_queue",
        "drivers/iommu/iova.c:init_iova_domain",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm-stats.c:dm_stats_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc",
        "drivers/hv/hv_common.c:hv_common_init",
        "drivers/hv/hv_common.c:hv_common_init",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/af_inet6.c:inet6_net_init",
        "net/ipv6/af_inet6.c:inet6_net_init",
        "net/ipv6/af_inet6.c:inet6_net_init",
        "net/ipv6/af_inet6.c:inet6_net_init",
        "net/ipv6/addrconf.c:ipv6_add_dev",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "net/packet/af_packet.c:packet_create",
        "net/mptcp/mib.c:mptcp_mib_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581774080,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582157520,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1948",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/build_utility.c:psi_cgroup_alloc",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/matrix.c:irq_alloc_matrix",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/relay.c:relay_open",
        "kernel/trace/trace.c:allocate_trace_buffer",
        "kernel/trace/trace.c:trace_array_init_printk",
        "kernel/trace/trace_functions.c:func_set_flag",
        "kernel/trace/trace_functions.c:function_trace_init",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/devmap.c:dev_map_notification",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/shmem.c:shmem_fill_super",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:free_area_init_core_hotplug",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create",
        "block/bdev.c:bdev_alloc",
        "block/bio.c:bioset_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-iocost.c:blk_iocost_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/dma-iommu.c:iommu_dma_init_fq",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm-stats.c:dm_stats_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc",
        "drivers/hv/hv_common.c:hv_common_init",
        "drivers/hv/hv_common.c:hv_common_init",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/af_inet6.c:inet6_net_init",
        "net/ipv6/af_inet6.c:inet6_net_init",
        "net/ipv6/af_inet6.c:inet6_net_init",
        "net/ipv6/af_inet6.c:inet6_net_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "net/packet/af_packet.c:packet_create",
        "net/mptcp/mib.c:mptcp_mib_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582157520,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582637360,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1941",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_event_ibs_init",
        "arch/x86/events/amd/ibs.c:perf_event_ibs_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/build_utility.c:psi_cgroup_alloc",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/matrix.c:irq_alloc_matrix",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/relay.c:relay_open",
        "kernel/trace/trace.c:allocate_trace_buffer",
        "kernel/trace/trace.c:trace_array_init_printk",
        "kernel/trace/trace_functions.c:func_set_flag",
        "kernel/trace/trace_functions.c:function_trace_init",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_event_perf.c:perf_trace_event_reg",
        "kernel/trace/trace_event_perf.c:perf_trace_event_reg",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:uprobe_buffer_init",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/devmap.c:dev_map_notification",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/shmem.c:shmem_fill_super",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:free_area_init_core_hotplug",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create",
        "block/bdev.c:bdev_alloc",
        "block/bio.c:bioset_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/dma-iommu.c:iommu_dma_init_fq",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm-stats.c:dm_stats_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc",
        "drivers/hv/hv_common.c:hv_common_init",
        "drivers/hv/hv_common.c:hv_common_init",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "net/packet/af_packet.c:packet_create",
        "net/mptcp/mib.c:mptcp_mib_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582637360,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582846608,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1941",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_event_ibs_init",
        "arch/x86/events/amd/ibs.c:perf_event_ibs_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/fork.c:mm_init",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/build_utility.c:psi_cgroup_alloc",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/matrix.c:irq_alloc_matrix",
        "kernel/rcu/srcutree.c:srcu_module_notify",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/relay.c:relay_open",
        "kernel/trace/trace.c:allocate_trace_buffer",
        "kernel/trace/trace.c:trace_array_init_printk",
        "kernel/trace/trace_functions.c:func_set_flag",
        "kernel/trace/trace_functions.c:function_trace_init",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_event_perf.c:perf_trace_event_reg",
        "kernel/trace/trace_event_perf.c:perf_trace_event_reg",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:uprobe_buffer_init",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/devmap.c:dev_map_notification",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/shmem.c:shmem_fill_super",
        "mm/mm_init.c:free_area_init_core_hotplug",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create",
        "block/bdev.c:bdev_alloc",
        "block/bio.c:bioset_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-iocost.c:blk_iocost_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/dma-iommu.c:iommu_dma_init_fq",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm-stats.c:dm_stats_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc",
        "drivers/hv/hv_common.c:hv_common_init",
        "drivers/hv/hv_common.c:hv_common_init",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/page_pool.c:page_pool_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "net/packet/af_packet.c:packet_create",
        "net/mptcp/mib.c:mptcp_mib_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582846608,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583021104,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1941",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_event_ibs_init",
        "arch/x86/events/amd/ibs.c:perf_event_ibs_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/fork.c:mm_init",
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/core.c:sched_tick_offload_init",
        "kernel/sched/build_utility.c:psi_cgroup_alloc",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/matrix.c:irq_alloc_matrix",
        "kernel/rcu/srcutree.c:srcu_module_notify",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/crash_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/relay.c:relay_open",
        "kernel/trace/trace.c:allocate_trace_buffer",
        "kernel/trace/trace.c:trace_array_init_printk",
        "kernel/trace/trace_functions.c:func_set_flag",
        "kernel/trace/trace_functions.c:function_trace_init",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_event_perf.c:perf_trace_event_reg",
        "kernel/trace/trace_event_perf.c:perf_trace_event_reg",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:uprobe_buffer_init",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/devmap.c:dev_map_notification",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/shmem.c:shmem_fill_super",
        "mm/mm_init.c:free_area_init_core_hotplug",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/slub.c:kmem_cache_open",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create",
        "block/bdev.c:bdev_alloc",
        "block/bio.c:bioset_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-iocost.c:blk_iocost_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/dma-iommu.c:iommu_dma_init_fq",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm-stats.c:dm_stats_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc",
        "drivers/hv/hv_common.c:hv_common_init",
        "drivers/hv/hv_common.c:hv_common_init",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/page_pool.c:page_pool_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "net/packet/af_packet.c:packet_create",
        "net/mptcp/mib.c:mptcp_mib_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583021104,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492661672,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1794",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/fpsimd.c:sve_setup",
        "virt/kvm/arm/arm.c:kvm_arch_init_vm",
        "arch/arm/xen/enlighten.c:xen_guest_init",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/psi.c:psi_cgroup_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-iocost.c:blk_iocost_init",
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/iommu/iova.c:init_iova_flush_queue",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm-stats.c:dm_stats_init",
        "drivers/firmware/arm_sdei.c:sdei_event_register",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_register",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492661672,
      "name": "__alloc_percpu",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226500020,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1794",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/smp_twd.c:twd_local_timer_of_register",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/psi.c:psi_cgroup_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:__se_sys_io_setup",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-iocost.c:blk_iocost_init",
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm-stats.c:dm_stats_init",
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init",
        "drivers/clocksource/timer-qcom.c:msm_dt_timer_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_of_init",
        "drivers/clocksource/arm_global_timer.c:global_timer_of_register",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226500020,
      "name": "__alloc_percpu",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285978432,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1794",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/psi.c:psi_cgroup_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-iocost.c:blk_iocost_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm-stats.c:dm_stats_init",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285978432,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272669796,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1794",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/psi.c:psi_cgroup_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/trace_event_perf.c:perf_trace_init",
        "kernel/trace/trace_event_perf.c:perf_trace_init",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/devmap.c:dev_map_init_map",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:__se_sys_io_setup",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-iocost.c:blk_iocost_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm-stats.c:dm_stats_init",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272669796,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581227328,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1794",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/psi.c:psi_cgroup_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/matrix.c:irq_alloc_matrix",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-iocost.c:blk_iocost_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/iova.c:init_iova_flush_queue",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm-stats.c:dm_stats_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581227328,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581174000,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1794",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/core.c:sched_tick_offload_init",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/psi.c:psi_cgroup_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/matrix.c:irq_alloc_matrix",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-iocost.c:blk_iocost_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/iommu/iova.c:init_iova_flush_queue",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm-stats.c:dm_stats_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc",
        "drivers/hv/hv.c:hv_init",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581174000,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581218528,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1794",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/psi.c:psi_cgroup_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/matrix.c:irq_alloc_matrix",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-iocost.c:blk_iocost_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/iova.c:init_iova_flush_queue",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm-stats.c:dm_stats_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/netfilter/nf_conntrack_core.c:nf_conntrack_init_net",
        "net/netfilter/nf_conntrack_core.c:nf_conntrack_init_net",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218528,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * __alloc_percpu(size_t size, size_t align)
```

```json
{
  "name": "__alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581281952,
      "name": "__alloc_percpu",
      "external": true,
      "loc": "mm/percpu.c:1794",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/acpi/cstate.c:ffh_cstate_init",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/psi.c:psi_cgroup_alloc",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/matrix.c:irq_alloc_matrix",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/kexec_core.c:crash_notes_memory_init",
        "kernel/cgroup/rstat.c:cgroup_rstat_init",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_init",
        "kernel/events/core.c:perf_cgroup_css_alloc",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/zswap.c:zswap_pool_create",
        "mm/slub.c:kmem_cache_open",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/aio.c:ioctx_alloc",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_alloc_callback",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-throttle.c:blk_throtl_init",
        "block/blk-iocost.c:blk_iocost_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/iova.c:init_iova_flush_queue",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/md/dm-stats.c:dm_stats_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/sock.c:sock_inuse_init_net",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/neighbour.c:neigh_table_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/fib_trie.c:fib_trie_table",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581281952,
      "name": "__alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
