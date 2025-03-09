# Function: <code>static_key_slow_dec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580463072,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:97",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/sched/core.c:sched_feat_write",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:__clear_sched_clock_stable",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/cpuset.c:cpuset_css_offline",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "drivers/i2c/i2c-core.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/dev.c:net_enable_timestamp",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:nf_unregister_net_hook",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata",
        "net/ipv4/tcp_memcontrol.c:tcp_destroy_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580463072,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580538528,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:171",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/sched/clock.c:__clear_sched_clock_stable",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/cpuset.c:cpuset_css_offline",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/events/core.c:sw_perf_event_destroy",
        "kernel/jump_label.c:static_key_disable",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "drivers/i2c/i2c-core.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_enable_timestamp",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:nf_unregister_net_hook",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580538528,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580602560,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:171",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/sched/clock.c:__clear_sched_clock_stable",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/cpuset.c:cpuset_css_offline",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/bpf/cgroup.c:__cgroup_bpf_update",
        "kernel/bpf/cgroup.c:cgroup_bpf_put",
        "kernel/events/core.c:sw_perf_event_destroy",
        "kernel/jump_label.c:static_key_disable",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "drivers/i2c/i2c-core.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:nf_unregister_net_hook",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602560,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580632416,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:177",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/sched/fair.c:cfs_bandwidth_usage_dec",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/bpf/cgroup.c:__cgroup_bpf_update",
        "kernel/bpf/cgroup.c:cgroup_bpf_put",
        "kernel/events/core.c:sw_perf_event_destroy",
        "kernel/jump_label.c:static_key_disable",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580632416,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580713840,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:225",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/tracepoint.c:trace_resched_ipi_unreg",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_unreg",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_put",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580713840,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580845952,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:226",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/tracepoint.c:trace_resched_ipi_unreg",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_unreg",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_put",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845952,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914768,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:249",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/tracepoint.c:trace_resched_ipi_unreg",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_unreg",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_put",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata",
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914768,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581013040,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:267",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/tracepoint.c:trace_resched_ipi_unreg",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_unreg",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata",
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013040,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581069424,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:267",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/tracepoint.c:trace_resched_ipi_unreg",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_unreg",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata",
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069424,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581249152,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:267",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_unreg",
        "kernel/sysctl.c:bpf_stats_handler",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/tracepoint.c:tracepoint_remove_func",
        "kernel/bpf/syscall.c:bpf_stats_release",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata",
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581249152,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581291120,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:267",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_unreg",
        "kernel/sysctl.c:bpf_stats_handler",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/bpf/syscall.c:bpf_stats_release",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memremap.c:memunmap_pages",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata",
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581291120,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581308784,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:267",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_unreg",
        "kernel/sysctl.c:bpf_stats_handler",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/bpf/syscall.c:bpf_stats_release",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memremap.c:memunmap_pages",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:udp_encap_disable",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata",
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308784,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:267",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_unreg",
        "kernel/sysctl.c:bpf_stats_handler",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/bpf/syscall.c:bpf_stats_release",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memremap.c:memunmap_pages",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:udp_encap_disable",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata",
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592188911,
      "name": "static_key_slow_dec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581553824,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:267",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_unreg",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/bpf/syscall.c:bpf_stats_handler",
        "kernel/bpf/syscall.c:bpf_stats_release",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/hugetlb_vmemmap.c:hugetlb_optimize_vmemmap_handler",
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_free",
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_alloc",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memremap.c:memunmap_pages",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/sched/cls_api.c:tc_skb_ext_tc_disable",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:udp_encap_disable",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata",
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593964010,
      "name": "static_key_slow_dec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581905536,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:295",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_unreg",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state",
        "kernel/cgroup/legacy_freezer.c:freezer_css_offline",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/bpf/syscall.c:bpf_stats_handler",
        "kernel/bpf/syscall.c:bpf_stats_release",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize",
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_restore",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memremap.c:memunmap_pages",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/sched/cls_api.c:tc_skb_ext_tc_disable",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:udp_encap_disable",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596023656,
      "name": "static_key_slow_dec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582339872,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:295",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_unreg",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/power/process.c:thaw_processes",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/bpf/syscall.c:bpf_stats_handler",
        "kernel/bpf/syscall.c:bpf_stats_release",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/page_alloc.c:try_to_accept_memory",
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize",
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_restore",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memremap.c:memunmap_pages",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask",
        "net/sched/cls_api.c:tc_skb_ext_tc_disable",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:udp_encap_disable",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596545942,
      "name": "static_key_slow_dec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582541840,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:295",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_unreg",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/power/process.c:thaw_processes",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/bpf/syscall.c:bpf_stats_handler",
        "kernel/bpf/syscall.c:bpf_stats_release",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/page_alloc.c:try_to_accept_memory",
        "mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio",
        "mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_restore_folio",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memremap.c:memunmap_pages",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:tcx_dec",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask",
        "net/sched/cls_api.c:tc_skb_ext_tc_disable",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:udp_encap_disable",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597449721,
      "name": "static_key_slow_dec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582710992,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492430352,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:267",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_free",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata",
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492430352,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
  "name": "static_key_slow_dec",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225065104,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 3225567112,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 3225736032,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 3226202160,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3226219256,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:sw_perf_event_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 3226821984,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3233360448,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg"
      ],
      "caller_func": []
    },
    {
      "addr": 3234637928,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3234730140,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3234769456,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:clean_xps_maps",
        "net/core/dev.c:clean_xps_maps",
        "net/core/dev.c:net_disable_timestamp",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3235002436,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3235408976,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:clean_acked_data_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 3235550632,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235700760,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 3236071468,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 3236175388,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:fl_free"
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285698720,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:267",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal-call.c:opal_tracepoint_unregfunc",
        "arch/powerpc/platforms/pseries/lpar.c:hcall_tracepoint_unregfunc",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata",
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285698720,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
  "name": "static_key_slow_dec",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271654208,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272011550,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272102750,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272443232,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272451304,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:sw_perf_event_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272969594,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277648332,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278196944,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278274692,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278309088,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:clean_xps_maps",
        "net/core/dev.c:clean_xps_maps",
        "net/core/dev.c:net_disable_timestamp",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278499614,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278837098,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:clean_acked_data_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278955638,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279084174,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279403662,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279490844,
      "name": "static_key_slow_dec",
      "external": false,
      "loc": "include/linux/jump_label.h:282",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:fl_free"
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581038272,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:267",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/tracepoint.c:trace_resched_ipi_unreg",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_unreg",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata",
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038272,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580984352,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:267",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/tracepoint.c:trace_resched_ipi_unreg",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_unreg",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata",
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984352,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581029472,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:267",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/tracepoint.c:trace_resched_ipi_unreg",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_unreg",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata",
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029472,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void static_key_slow_dec(struct static_key * key)
```

```json
{
  "name": "static_key_slow_dec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090896,
      "name": "static_key_slow_dec",
      "external": true,
      "loc": "kernel/jump_label.c:267",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/tracepoint.c:trace_resched_ipi_unreg",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_unreg",
        "kernel/sched/core.c:preempt_notifier_dec",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/events/core.c:sw_perf_event_destroy",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_unregister_net_hook",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata",
        "net/ipv6/udp.c:udpv6_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090896,
      "name": "static_key_slow_dec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void static_key_slow_dec(struct static_key * key)
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
void static_key_slow_dec(struct static_key * key)
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
