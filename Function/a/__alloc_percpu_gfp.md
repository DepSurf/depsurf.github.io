# Function: <code>__alloc_percpu_gfp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580620368,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1067",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/xen-netfront.c:netfront_probe",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_hash_create",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580620368,
      "name": "__alloc_percpu_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580723120,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1060",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/xen-netfront.c:netfront_probe",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_hash_create",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580723120,
      "name": "__alloc_percpu_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580788944,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1064",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/xen-netfront.c:netfront_probe",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_hash_create",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580788944,
      "name": "__alloc_percpu_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580827632,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1064",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/xen-netfront.c:netfront_probe",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_hash_create",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580827632,
      "name": "__alloc_percpu_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580920368,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1524",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/xen-netfront.c:netfront_probe",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920368,
      "name": "__alloc_percpu_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581054496,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1533",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/devmap.c:dev_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/xen-netfront.c:netfront_probe",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv6/ip6_fib.c:fib6_info_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581054496,
      "name": "__alloc_percpu_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581132288,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1544",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/devmap.c:dev_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/xen-netfront.c:netfront_probe",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv6/ip6_fib.c:fib6_info_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581132288,
      "name": "__alloc_percpu_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581199984,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1781",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/devmap.c:dev_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/xen-netfront.c:netfront_probe",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581199984,
      "name": "__alloc_percpu_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581258448,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1781",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/xen-netfront.c:netfront_probe",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_traps_register",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581258448,
      "name": "__alloc_percpu_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581447696,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1758",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/devmap.c:dev_map_notification",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/core/devlink.c:devlink_trap_group_register",
        "net/core/devlink.c:devlink_trap_register",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581447696,
      "name": "__alloc_percpu_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581491520,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1891",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/syscall.c:bpf_map_alloc_percpu",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:alloc_mem_cgroup_per_node_info",
        "mm/memcontrol.c:alloc_mem_cgroup_per_node_info",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-iocost.c:ioc_pd_alloc",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/core/devlink.c:devlink_trap_group_register",
        "net/core/devlink.c:devlink_trap_register",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581491520,
      "name": "__alloc_percpu_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581510944,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1892",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "kernel/bpf/syscall.c:bpf_map_alloc_percpu",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-iocost.c:ioc_pd_alloc",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "lib/sbitmap.c:sbitmap_init_node",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/core/devlink.c:devlink_trap_groups_register",
        "net/core/devlink.c:devlink_traps_register",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/seg6_local.c:parse_nla_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510944,
      "name": "__alloc_percpu_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581774048,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1935",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "kernel/bpf/syscall.c:bpf_map_alloc_percpu",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-iocost.c:ioc_pd_alloc",
        "block/mq-deadline.c:dd_init_sched",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "lib/sbitmap.c:sbitmap_init_node",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/tun.c:tun_net_init",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/core/devlink.c:devlink_trap_groups_register",
        "net/core/devlink.c:devlink_traps_register",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/seg6_local.c:parse_nla_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581774048,
      "name": "__alloc_percpu_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582157488,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1935",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "kernel/bpf/syscall.c:bpf_map_alloc_percpu",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-iocost.c:ioc_pd_alloc",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "lib/sbitmap.c:sbitmap_init_node",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/tun.c:tun_net_init",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "net/core/dev.c:netdev_core_stats_alloc",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/core/devlink.c:devlink_trap_groups_register",
        "net/core/devlink.c:devlink_traps_register",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/fib_semantics.c:fib_nh_common_init",
        "net/ipv6/addrconf.c:ipv6_add_dev",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/seg6_local.c:parse_nla_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582157488,
      "name": "__alloc_percpu_gfp",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582637312,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1928",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "kernel/bpf/syscall.c:bpf_map_alloc_percpu",
        "kernel/bpf/memalloc.c:bpf_mem_alloc_init",
        "kernel/bpf/memalloc.c:bpf_mem_alloc_init",
        "kernel/bpf/memalloc.c:__alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "block/blk-cgroup.c:blkcg_css_alloc",
        "block/blk-cgroup.c:blkcg_css_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-iocost.c:ioc_pd_alloc",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "lib/sbitmap.c:sbitmap_init_node",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/tun.c:tun_net_init",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "net/core/dev.c:netdev_core_stats_alloc",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/core/devlink.c:devl_trap_groups_register",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/fib_semantics.c:fib_nh_common_init",
        "net/ipv6/addrconf.c:snmp6_alloc_dev",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/seg6_local.c:parse_nla_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582637312,
      "name": "__alloc_percpu_gfp",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582846560,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1928",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "kernel/bpf/syscall.c:bpf_map_alloc_percpu",
        "kernel/bpf/memalloc.c:bpf_mem_alloc_init",
        "kernel/bpf/memalloc.c:bpf_mem_alloc_init",
        "kernel/bpf/memalloc.c:__alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "block/blk-cgroup.c:blkcg_css_alloc",
        "block/blk-cgroup.c:blkcg_css_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-iocost.c:ioc_pd_alloc",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "lib/sbitmap.c:sbitmap_init_node",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/tun.c:tun_net_init",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "net/core/dev.c:netdev_core_stats_alloc",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/fib_semantics.c:fib_nh_common_init",
        "net/ipv6/addrconf.c:snmp6_alloc_dev",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/seg6_local.c:parse_nla_counters",
        "net/devlink/leftover.c:devl_trap_groups_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582846560,
      "name": "__alloc_percpu_gfp",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583021056,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1928",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "kernel/bpf/syscall.c:bpf_map_alloc_percpu",
        "kernel/bpf/memalloc.c:bpf_mem_alloc_percpu_init",
        "kernel/bpf/memalloc.c:bpf_mem_alloc_init",
        "kernel/bpf/memalloc.c:bpf_mem_alloc_init",
        "kernel/bpf/memalloc.c:__alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "block/blk-cgroup.c:blkcg_css_alloc",
        "block/blk-cgroup.c:blkcg_css_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-iocost.c:ioc_pd_alloc",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init_many",
        "lib/sbitmap.c:sbitmap_init_node",
        "drivers/spi/spi.c:spi_alloc_device",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/tun.c:tun_net_init",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "net/core/dev.c:netdev_core_stats_inc",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/fib_semantics.c:fib_nh_common_init",
        "net/ipv6/addrconf.c:snmp6_alloc_dev",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/seg6_local.c:parse_nla_counters",
        "net/devlink/trap.c:devl_trap_groups_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583021056,
      "name": "__alloc_percpu_gfp",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492661600,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1781",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/xen-netfront.c:netfront_probe",
        "drivers/net/xen-netfront.c:netfront_probe",
        "drivers/perf/arm_pmu.c:__armpmu_alloc",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_traps_register",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492661600,
      "name": "__alloc_percpu_gfp",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226499984,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1781",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/perf/arm_pmu.c:__armpmu_alloc",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_traps_register",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226499984,
      "name": "__alloc_percpu_gfp",
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285978400,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1781",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_traps_register",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285978400,
      "name": "__alloc_percpu_gfp",
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272669736,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1781",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_traps_register",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272669736,
      "name": "__alloc_percpu_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581227296,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1781",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/xen-netfront.c:netfront_probe",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_traps_register",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581227296,
      "name": "__alloc_percpu_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581173968,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1781",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/vxlan.c:vxlan_init",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_traps_register",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv4/ip_tunnel.c:ip_tunnel_init",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581173968,
      "name": "__alloc_percpu_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581218496,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1781",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/xen-netfront.c:netfront_probe",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_traps_register",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218496,
      "name": "__alloc_percpu_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void * __alloc_percpu_gfp(size_t size, size_t align, gfp_t gfp)
```

```json
{
  "name": "__alloc_percpu_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581281920,
      "name": "__alloc_percpu_gfp",
      "external": true,
      "loc": "mm/percpu.c:1781",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_functions_graph.c:graph_trace_open",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "lib/percpu-refcount.c:percpu_ref_init",
        "lib/percpu_counter.c:__percpu_counter_init",
        "drivers/net/loopback.c:loopback_dev_init",
        "drivers/net/xen-netfront.c:netfront_probe",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dst.c:metadata_dst_alloc_percpu",
        "net/core/dst_cache.c:dst_cache_init",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_traps_register",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581281920,
      "name": "__alloc_percpu_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
