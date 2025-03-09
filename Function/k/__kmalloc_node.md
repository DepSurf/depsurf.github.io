# Function: <code>__kmalloc_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580864720,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:3557",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "mm/mempool.c:mempool_create_node",
        "mm/mempool.c:mempool_create_node",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "security/apparmor/lsm.c:alloc_buffers",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_init_rq_map",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq-tag.c:bt_alloc",
        "block/blk-mq-cpumap.c:blk_mq_make_queue_map",
        "block/genhd.c:disk_expand_part_tbl",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "lib/genalloc.c:gen_pool_add_virt",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:netif_set_xps_queue",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:qdisc_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864720,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580983888,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:3740",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:get_callchain_buffers",
        "mm/mempool.c:mempool_create_node",
        "mm/mempool.c:mempool_create_node",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "security/apparmor/lsm.c:alloc_buffers",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_init_rq_map",
        "block/blk-mq-cpumap.c:blk_mq_make_queue_map",
        "block/genhd.c:disk_expand_part_tbl",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "lib/genalloc.c:gen_pool_add_virt",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:netif_set_xps_queue",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:qdisc_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580983888,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581057728,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:3762",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:get_callchain_buffers",
        "mm/mempool.c:mempool_create_node",
        "mm/mempool.c:mempool_create_node",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_init_rq_map",
        "block/genhd.c:disk_expand_part_tbl",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "lib/cpumask.c:alloc_cpumask_var_node",
        "lib/genalloc.c:gen_pool_add_virt",
        "lib/sbitmap.c:sbitmap_init_node",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:netif_set_xps_queue",
        "net/core/flow.c:flow_cache_cpu_up_prep",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:qdisc_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581057728,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581111456,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:3767",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:get_callchain_buffers",
        "mm/mempool.c:mempool_create_node",
        "mm/mempool.c:mempool_create_node",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "block/blk-core.c:alloc_request_size",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/genhd.c:disk_expand_part_tbl",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "lib/genalloc.c:gen_pool_add_virt",
        "lib/sbitmap.c:sbitmap_init_node",
        "drivers/md/dm.c:dm_create",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:netif_set_xps_queue",
        "net/core/flow.c:flow_cache_cpu_up_prep",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "lib/cpumask.c:alloc_cpumask_var_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581111456,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581226448,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:3783",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/syscall.c:bpf_map_area_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:get_callchain_buffers",
        "mm/mempool.c:mempool_create_node",
        "mm/mempool.c:mempool_create_node",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "block/blk-core.c:alloc_request_size",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/genhd.c:disk_expand_part_tbl",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "lib/genalloc.c:gen_pool_add_virt",
        "lib/sbitmap.c:sbitmap_init_node",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:netif_set_xps_queue",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "lib/cpumask.c:alloc_cpumask_var_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581226448,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 698
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
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581364384,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:3774",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/syscall.c:bpf_map_area_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:get_callchain_buffers",
        "mm/mempool.c:mempool_create_node",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "security/apparmor/lsm.c:apparmor_init",
        "block/blk-core.c:alloc_request_size",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/genhd.c:disk_expand_part_tbl",
        "block/blk-throttle.c:throtl_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "lib/genalloc.c:gen_pool_add_virt",
        "lib/sbitmap.c:sbitmap_init_node",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:netif_set_xps_queue",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "lib/cpumask.c:alloc_cpumask_var_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581364384,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 702
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
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581449600,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:3824",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/syscall.c:bpf_map_area_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:get_callchain_buffers",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/memblock.c:memblock_alloc_internal",
        "security/apparmor/lsm.c:alloc_buffers",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/genhd.c:disk_expand_part_tbl",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "lib/sbitmap.c:sbitmap_init_node",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "lib/cpumask.c:alloc_cpumask_var_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581449600,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 685
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
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581563104,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:3831",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/syscall.c:bpf_map_area_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:alloc_callchain_buffers",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/memblock.c:memblock_alloc_internal",
        "security/apparmor/lsm.c:apparmor_init",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/genhd.c:disk_expand_part_tbl",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "lib/sbitmap.c:sbitmap_init_node",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "lib/cpumask.c:alloc_cpumask_var_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581563104,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 793
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
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581628128,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:3845",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/syscall.c:bpf_map_area_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:alloc_callchain_buffers",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/memblock.c:memblock_alloc_internal",
        "security/apparmor/lsm.c:apparmor_init",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/genhd.c:disk_expand_part_tbl",
        "block/blk-iocost.c:ioc_pd_alloc",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "lib/sbitmap.c:sbitmap_init_node",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "lib/cpumask.c:alloc_cpumask_var_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581628128,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 793
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
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581845120,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:3922",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:build_group_from_child_sched_domain",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/syscall.c:__bpf_map_area_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc",
        "kernel/events/core.c:perf_cgroup_ensure_storage",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:alloc_callchain_buffers",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/memblock.c:memblock_alloc_internal",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/genhd.c:disk_expand_part_tbl",
        "block/blk-iocost.c:ioc_pd_alloc",
        "block/blk-zoned.c:blk_revalidate_zone_cb",
        "block/blk-zoned.c:blk_revalidate_zone_cb",
        "lib/sbitmap.c:sbitmap_init_node",
        "lib/cpumask.c:alloc_cpumask_var_node",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_add_in_port",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/sock_map.c:sock_hash_alloc_elem",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581845120,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 761
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
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581897424,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:4009",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:build_group_from_child_sched_domain",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/syscall.c:bpf_map_kmalloc_node",
        "kernel/bpf/syscall.c:__bpf_map_area_alloc",
        "kernel/events/core.c:perf_cgroup_ensure_storage",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:alloc_callchain_buffers",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memcontrol.c:memcg_alloc_page_obj_cgroups",
        "crypto/api.c:crypto_create_tfm_node",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/genhd.c:disk_expand_part_tbl",
        "block/blk-iocost.c:ioc_pd_alloc",
        "block/blk-zoned.c:blk_revalidate_zone_cb",
        "block/blk-zoned.c:blk_revalidate_zone_cb",
        "lib/sbitmap.c:sbitmap_init_node",
        "lib/cpumask.c:alloc_cpumask_var_node",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_add_in_port",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581897424,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 685
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
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581926656,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:4078",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/syscall.c:bpf_map_kmalloc_node",
        "kernel/bpf/syscall.c:__bpf_map_area_alloc",
        "kernel/events/core.c:perf_cgroup_ensure_storage",
        "kernel/events/ring_buffer.c:rb_alloc",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:alloc_callchain_buffers",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memcontrol.c:memcg_alloc_page_obj_cgroups",
        "crypto/api.c:crypto_create_tfm_node",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-iocost.c:ioc_pd_alloc",
        "block/blk-zoned.c:blk_revalidate_zone_cb",
        "block/blk-zoned.c:blk_revalidate_zone_cb",
        "lib/sbitmap.c:sbitmap_init_node",
        "lib/cpumask.c:alloc_cpumask_var_node",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_add_in_port",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:expand_xps_map",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926656,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 757
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:4424",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers",
        "kernel/sched/core.c:dup_user_cpus_ptr",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:__sdt_alloc",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/syscall.c:bpf_map_kmalloc_node",
        "kernel/bpf/syscall.c:__bpf_map_area_alloc",
        "kernel/events/core.c:perf_cgroup_ensure_storage",
        "kernel/events/ring_buffer.c:rb_alloc",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:alloc_callchain_buffers",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memcontrol.c:memcg_alloc_page_obj_cgroups",
        "crypto/api.c:crypto_create_tfm_node",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-iocost.c:ioc_pd_alloc",
        "block/blk-zoned.c:blk_revalidate_zone_cb",
        "block/blk-zoned.c:blk_revalidate_zone_cb",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated",
        "lib/sbitmap.c:sbitmap_init_node",
        "lib/cpumask.c:alloc_cpumask_var_node",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_add_in_port",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:expand_xps_map",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592221320,
      "name": "__kmalloc_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582221488,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 915
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:4470",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers",
        "kernel/sched/core.c:dup_user_cpus_ptr",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/syscall.c:bpf_map_kmalloc_node",
        "kernel/bpf/syscall.c:__bpf_map_area_alloc",
        "kernel/events/core.c:perf_cgroup_ensure_storage",
        "kernel/events/ring_buffer.c:rb_alloc",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:alloc_callchain_buffers",
        "mm/mempool.c:mempool_init_node",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memcontrol.c:memcg_alloc_slab_cgroups",
        "crypto/api.c:crypto_create_tfm_node",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_realloc_tag_set_tags",
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "block/blk-ia-ranges.c:disk_alloc_independent_access_ranges",
        "block/blk-iocost.c:ioc_pd_alloc",
        "block/blk-zoned.c:blk_revalidate_zone_cb",
        "block/blk-zoned.c:blk_revalidate_zone_cb",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated",
        "lib/bitmap.c:bitmap_zalloc_node",
        "lib/cpumask.c:alloc_cpumask_var_node",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_add_in_port",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:expand_xps_map",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594000210,
      "name": "__kmalloc_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582688080,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1039
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slab_common.c:973",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers",
        "kernel/sched/core.c:alloc_user_cpus_ptr",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/syscall.c:bpf_map_kmalloc_node",
        "kernel/bpf/syscall.c:__bpf_map_area_alloc",
        "kernel/bpf/memalloc.c:__alloc",
        "kernel/bpf/memalloc.c:__alloc",
        "kernel/events/ring_buffer.c:rb_alloc",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:alloc_callchain_buffers",
        "mm/mempool.c:mempool_init_node",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memcontrol.c:memcg_alloc_slab_cgroups",
        "crypto/api.c:crypto_create_tfm_node",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_realloc_tag_set_tags",
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "block/blk-ia-ranges.c:disk_alloc_independent_access_ranges",
        "block/blk-iocost.c:ioc_pd_alloc",
        "block/blk-zoned.c:blk_revalidate_zone_cb",
        "block/blk-zoned.c:blk_revalidate_zone_cb",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated",
        "lib/bitmap.c:bitmap_zalloc_node",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_add_in_port",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:expand_xps_map",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "lib/cpumask.c:alloc_cpumask_var_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596028647,
      "name": "__kmalloc_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071582654224,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slab_common.c:990",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers",
        "kernel/sched/core.c:alloc_user_cpus_ptr",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/syscall.c:bpf_map_kmalloc_node",
        "kernel/bpf/syscall.c:__bpf_map_area_alloc",
        "kernel/bpf/memalloc.c:__alloc",
        "kernel/bpf/memalloc.c:__alloc",
        "kernel/events/ring_buffer.c:rb_alloc",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:alloc_callchain_buffers",
        "mm/mempool.c:mempool_init_node",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memcontrol.c:memcg_alloc_slab_cgroups",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_realloc_tag_set_tags",
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "block/blk-ia-ranges.c:disk_alloc_independent_access_ranges",
        "block/blk-iocost.c:ioc_pd_alloc",
        "block/blk-zoned.c:blk_revalidate_zone_cb",
        "block/blk-zoned.c:blk_revalidate_zone_cb",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated",
        "lib/bitmap.c:bitmap_zalloc_node",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_add_in_port",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:expand_xps_map",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "lib/cpumask.c:alloc_cpumask_var_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596550972,
      "name": "__kmalloc_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071582864272,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:3986",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers",
        "kernel/sched/core.c:alloc_user_cpus_ptr",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:__sdt_alloc",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/syscall.c:bpf_map_kmalloc_node",
        "kernel/bpf/syscall.c:__bpf_map_area_alloc",
        "kernel/bpf/memalloc.c:__alloc",
        "kernel/bpf/memalloc.c:__alloc",
        "kernel/events/ring_buffer.c:rb_alloc",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:alloc_callchain_buffers",
        "mm/mempool.c:mempool_init_node",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memcontrol.c:memcg_alloc_slab_cgroups",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_realloc_tag_set_tags",
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "block/blk-ia-ranges.c:disk_alloc_independent_access_ranges",
        "block/blk-iocost.c:ioc_pd_alloc",
        "block/blk-zoned.c:blk_revalidate_zone_cb",
        "block/blk-zoned.c:blk_revalidate_zone_cb",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated",
        "lib/bitmap.c:bitmap_zalloc_node",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_add_in_port",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:expand_xps_map",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv4/tcp_sigpool.c:sigpool_reserve_scratch",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "lib/cpumask.c:alloc_cpumask_var_node",
        "lib/objpool.c:objpool_init_percpu_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597465742,
      "name": "__kmalloc_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071583415792,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1279
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
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493075344,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:3845",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/syscall.c:bpf_map_area_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:get_callchain_buffers",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/memblock.c:memblock_alloc_internal",
        "security/apparmor/lsm.c:alloc_buffers",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/genhd.c:disk_expand_part_tbl",
        "block/blk-iocost.c:ioc_pd_alloc",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "lib/sbitmap.c:sbitmap_init_node",
        "drivers/irqchip/irq-gic-v3-its.c:its_create_device",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_add_in_port",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493075344,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 724
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
  "name": "__kmalloc_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225235364,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226030656,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226117264,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 3226137100,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226142316,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226281472,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 3226283712,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 3226346828,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226466312,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226649636,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243451736,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_alloc_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243525308,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/elevator.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229171716,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:blk_alloc_flush_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3229217784,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-mq.c:blk_mq_alloc_rq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229248644,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:disk_expand_part_tbl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229351148,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_pd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/mq-deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229383012,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229687776,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_init_node"
      ],
      "caller_func": []
    },
    {
      "addr": 3229729228,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_create_device"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233082676,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "drivers/md/dm-rq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234729764,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3234768404,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235088148,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
      ],
      "caller_func": []
    },
    {
      "addr": 3235167440,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:qdisc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3244008584,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286518992,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:3845",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/bpf/syscall.c:bpf_map_area_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:alloc_callchain_buffers",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/memblock.c:memblock_alloc_internal",
        "security/apparmor/lsm.c:apparmor_init",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/genhd.c:disk_expand_part_tbl",
        "block/blk-iocost.c:ioc_pd_alloc",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "lib/sbitmap.c:sbitmap_init_node",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286518992,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1188
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
  "name": "__kmalloc_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271757102,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272298130,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272366534,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272387338,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272392058,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272504386,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272506130,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272540292,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272640766,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvmalloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272794748,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936270691548,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_alloc_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936270755842,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/elevator.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274956978,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:blk_alloc_flush_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274995714,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-mq.c:blk_mq_alloc_rq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275020892,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:disk_expand_part_tbl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275101396,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_pd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/mq-deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275129808,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275400524,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_init_node"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277490310,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "drivers/md/dm-rq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278274184,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278308810,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278567954,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278637858,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:qdisc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936270876444,
      "name": "__kmalloc_node",
      "external": false,
      "loc": "include/linux/slab.h:420",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581596864,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:3845",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/syscall.c:bpf_map_area_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:alloc_callchain_buffers",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/memblock.c:memblock_alloc_internal",
        "security/apparmor/lsm.c:apparmor_init",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/genhd.c:disk_expand_part_tbl",
        "block/blk-iocost.c:ioc_pd_alloc",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "lib/sbitmap.c:sbitmap_init_node",
        "drivers/nvme/host/pci.c:nvme_probe",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "lib/cpumask.c:alloc_cpumask_var_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581596864,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 793
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
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581538272,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:3845",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/syscall.c:bpf_map_area_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:alloc_callchain_buffers",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/memblock.c:memblock_alloc_internal",
        "security/apparmor/lsm.c:apparmor_init",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/genhd.c:disk_expand_part_tbl",
        "block/blk-iocost.c:ioc_pd_alloc",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "lib/sbitmap.c:sbitmap_init_node",
        "drivers/nvme/host/pci.c:nvme_probe",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "lib/cpumask.c:alloc_cpumask_var_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581538272,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 793
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
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581588176,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:3845",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/syscall.c:bpf_map_area_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:alloc_callchain_buffers",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/memblock.c:memblock_alloc_internal",
        "security/apparmor/lsm.c:apparmor_init",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/genhd.c:disk_expand_part_tbl",
        "block/blk-iocost.c:ioc_pd_alloc",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "lib/sbitmap.c:sbitmap_init_node",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "lib/cpumask.c:alloc_cpumask_var_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588176,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 793
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
void * __kmalloc_node(size_t size, gfp_t flags, int node)
```

```json
{
  "name": "__kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581650736,
      "name": "__kmalloc_node",
      "external": true,
      "loc": "mm/slub.c:3845",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/bts.c:bts_buffer_setup_aux",
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/bpf/syscall.c:bpf_map_area_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/lpm_trie.c:lpm_trie_node_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/callchain.c:alloc_callchain_buffers",
        "mm/util.c:kvmalloc_node",
        "mm/util.c:kvmalloc_node",
        "mm/memblock.c:memblock_alloc_internal",
        "security/apparmor/lsm.c:apparmor_init",
        "block/blk-flush.c:blk_alloc_flush_queue",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/blk-mq.c:blk_mq_alloc_rq_map",
        "block/genhd.c:disk_expand_part_tbl",
        "block/blk-iocost.c:ioc_pd_alloc",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "lib/sbitmap.c:sbitmap_init_node",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "lib/cpumask.c:alloc_cpumask_var_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581650736,
      "name": "__kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * __kmalloc_node(size_t size, gfp_t flags, int node)
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
void * __kmalloc_node(size_t size, gfp_t flags, int node)
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
