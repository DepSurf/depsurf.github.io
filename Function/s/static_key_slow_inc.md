# Function: <code>static_key_slow_inc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580462768,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:59",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/tsc.c:tsc_init",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/core.c:sched_feat_write",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:__set_sched_clock_stable",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/cpuset.c:cpuset_css_online",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/events/core.c:perf_swevent_init",
        "mm/memcontrol.c:memcg_activate_kmem",
        "drivers/i2c/i2c-core.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/dev.c:net_enable_timestamp",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:nf_register_net_hook",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv4/tcp_memcontrol.c:tcp_cgroup_write",
        "net/ipv6/udp.c:udpv6_encap_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580462768,
      "name": "static_key_slow_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580538144,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:103",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/clock.c:__set_sched_clock_stable",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/cpuset.c:cpuset_css_online",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/events/core.c:perf_swevent_init",
        "kernel/jump_label.c:static_key_enable",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_enable_timestamp",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:nf_register_net_hook",
        "net/ipv4/udp.c:udp_encap_enable",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580538144,
      "name": "static_key_slow_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580602176,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:103",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap",
        "arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/clock.c:__set_sched_clock_stable",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/cpuset.c:cpuset_css_online",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/bpf/cgroup.c:__cgroup_bpf_update",
        "kernel/events/core.c:perf_swevent_init",
        "kernel/jump_label.c:static_key_enable",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:nf_register_net_hook",
        "net/ipv4/udp.c:udp_encap_enable",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602176,
      "name": "static_key_slow_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580632048,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:104",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap",
        "arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/fair.c:cfs_bandwidth_usage_inc",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/bpf/cgroup.c:__cgroup_bpf_update",
        "kernel/events/core.c:perf_swevent_init",
        "kernel/jump_label.c:static_key_enable",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:nf_register_net_hook",
        "net/ipv4/udp.c:udp_encap_enable",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580632048,
      "name": "static_key_slow_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580715024,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:121",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap",
        "arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/tracepoint.c:trace_resched_ipi_reg",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_reg",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:nf_register_net_hook",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580715024,
      "name": "static_key_slow_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580847472,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:122",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap",
        "arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/tracepoint.c:trace_resched_ipi_reg",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_reg",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/ipv4/tcp_input.c:clean_acked_data_enable",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580847472,
      "name": "static_key_slow_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916336,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:141",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap",
        "arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/tracepoint.c:trace_resched_ipi_reg",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_reg",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/clock.c:sched_clock_init",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool",
        "net/ipv4/tcp_input.c:clean_acked_data_enable",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916336,
      "name": "static_key_slow_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581014416,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:156",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap",
        "arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/tracepoint.c:trace_resched_ipi_reg",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_reg",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/clock.c:sched_clock_init",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool",
        "net/ipv4/tcp_input.c:clean_acked_data_enable",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014416,
      "name": "static_key_slow_inc",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581069712,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:156",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap",
        "arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/tracepoint.c:trace_resched_ipi_reg",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_reg",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/clock.c:sched_clock_init",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool",
        "net/ipv4/tcp_input.c:clean_acked_data_enable",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069712,
      "name": "static_key_slow_inc",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581250640,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:156",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap",
        "arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/vmware.c:activate_jump_labels",
        "arch/x86/kernel/cpu/vmware.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_reg",
        "kernel/sysctl.c:bpf_stats_handler",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/clock.c:sched_clock_init",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/bpf/syscall.c:bpf_enable_stats",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool",
        "net/ipv4/tcp_input.c:clean_acked_data_enable",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581250640,
      "name": "static_key_slow_inc",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581292720,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:156",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/cpu/vmware.c:activate_jump_labels",
        "arch/x86/kernel/cpu/vmware.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_reg",
        "kernel/sysctl.c:bpf_stats_handler",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/clock.c:sched_clock_init",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/bpf/syscall.c:bpf_enable_stats",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memremap.c:memremap_pages",
        "arch/x86/lib/copy_mc.c:enable_copy_mc_fragile",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool",
        "net/ipv4/tcp_input.c:clean_acked_data_enable",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581292720,
      "name": "static_key_slow_inc",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581310352,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:156",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/cpu/vmware.c:activate_jump_labels",
        "arch/x86/kernel/cpu/vmware.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_reg",
        "kernel/sysctl.c:bpf_stats_handler",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/clock.c:sched_clock_init",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memremap.c:memremap_pages",
        "arch/x86/lib/copy_mc.c:enable_copy_mc_fragile",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool",
        "net/ipv4/tcp_input.c:clean_acked_data_enable",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581310352,
      "name": "static_key_slow_inc",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581555472,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:156",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/cpu/vmware.c:activate_jump_labels",
        "arch/x86/kernel/cpu/vmware.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_reg",
        "kernel/sysctl.c:bpf_stats_handler",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/clock.c:sched_clock_init",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memremap.c:memremap_pages",
        "arch/x86/lib/copy_mc.c:enable_copy_mc_fragile",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool",
        "net/ipv4/tcp_input.c:clean_acked_data_enable",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581555472,
      "name": "static_key_slow_inc",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581906960,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:156",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/cpu/vmware.c:activate_jump_labels",
        "arch/x86/kernel/cpu/vmware.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_reg",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/build_utility.c:sched_clock_init_late",
        "kernel/sched/build_utility.c:sched_clock_init",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/bpf/syscall.c:bpf_stats_handler",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/hugetlb_vmemmap.c:hugetlb_optimize_vmemmap_handler",
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memremap.c:memremap_pages",
        "arch/x86/lib/copy_mc.c:enable_copy_mc_fragile",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/sched/cls_api.c:tc_skb_ext_tc_enable",
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool",
        "net/ipv4/tcp_input.c:clean_acked_data_enable",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581906960,
      "name": "static_key_slow_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
bool static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582341392,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:181",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/cpu/vmware.c:activate_jump_labels",
        "arch/x86/kernel/cpu/vmware.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_reg",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/build_utility.c:sched_clock_init_late",
        "kernel/sched/build_utility.c:sched_clock_init",
        "kernel/power/process.c:freeze_processes",
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state",
        "kernel/cgroup/legacy_freezer.c:freezer_css_online",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/bpf/syscall.c:bpf_stats_handler",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memremap.c:memremap_pages",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/sched/cls_api.c:tc_skb_ext_tc_enable",
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/ipv4/tcp_input.c:clean_acked_data_enable",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "arch/x86/lib/copy_mc.c:enable_copy_mc_fragile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582341392,
      "name": "static_key_slow_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582543760,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:181",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/cpu/vmware.c:activate_jump_labels",
        "arch/x86/kernel/cpu/vmware.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_reg",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/build_utility.c:sched_clock_init_late",
        "kernel/sched/build_utility.c:sched_clock_init",
        "kernel/power/process.c:freeze_processes",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/bpf/syscall.c:bpf_stats_handler",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "mm/page_alloc.c:__free_pages_core",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memremap.c:memremap_pages",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask",
        "net/sched/cls_api.c:tc_skb_ext_tc_enable",
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/ipv4/tcp_input.c:clean_acked_data_enable",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "arch/x86/lib/copy_mc.c:enable_copy_mc_fragile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582543760,
      "name": "static_key_slow_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582712992,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:181",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/cpu/vmware.c:activate_jump_labels",
        "arch/x86/kernel/cpu/vmware.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_reg",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/build_utility.c:sched_clock_init_late",
        "kernel/sched/build_utility.c:sched_clock_init",
        "kernel/power/process.c:freeze_processes",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/bpf/syscall.c:bpf_stats_handler",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "kernel/context_tracking.c:ct_cpu_track_user",
        "mm/page_alloc.c:__free_pages_core",
        "mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memremap.c:memremap_pages",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:tcx_inc",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask",
        "net/sched/cls_api.c:tc_skb_ext_tc_enable",
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/ipv4/tcp_input.c:clean_acked_data_enable",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv4/tcp_ao.c:tcp_ao_add_cmd",
        "net/ipv6/udp.c:udpv6_encap_enable",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "arch/x86/lib/copy_mc.c:enable_copy_mc_fragile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582712992,
      "name": "static_key_slow_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492430808,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:156",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/clock.c:sched_clock_init",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool",
        "net/ipv4/tcp_input.c:clean_acked_data_enable",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492430808,
      "name": "static_key_slow_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
  "name": "static_key_slow_inc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243372764,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3225063584,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 3225563796,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online"
      ],
      "caller_func": []
    },
    {
      "addr": 3225736764,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ],
      "caller_func": []
    },
    {
      "addr": 3226201268,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 3226219800,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_swevent_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3226734176,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 3236531888,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3243544468,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "lib/crc-t10dif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crc-t10dif.c:crc_t10dif_mod_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3233360588,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 3234633732,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3234730392,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3234769708,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:net_enable_timestamp",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3235002384,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3235375196,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 3235409148,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:clean_acked_data_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3235553536,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 3235700896,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 3236071588,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_encap_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3236176616,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:fl_create"
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
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285700432,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:156",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal-call.c:opal_tracepoint_regfunc",
        "arch/powerpc/platforms/pseries/lpar.c:hcall_tracepoint_regfunc",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/clock.c:sched_clock_init",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool",
        "net/ipv4/tcp_input.c:clean_acked_data_enable",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285700432,
      "name": "static_key_slow_inc",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270626306,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271652996,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272013562,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272103424,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272442622,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272465514,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_swevent_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272865880,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279792030,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270770882,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "lib/crc-t10dif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crc-t10dif.c:crc_t10dif_mod_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277648438,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278193494,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278274920,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278309266,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:net_enable_timestamp",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278499588,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278809078,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278837198,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:clean_acked_data_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278957498,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279084280,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279403734,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_encap_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279491566,
      "name": "static_key_slow_inc",
      "external": false,
      "loc": "include/linux/jump_label.h:276",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:fl_create"
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
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581038560,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:156",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap",
        "arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/tracepoint.c:trace_resched_ipi_reg",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_reg",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/clock.c:sched_clock_init",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool",
        "net/ipv4/tcp_input.c:clean_acked_data_enable",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038560,
      "name": "static_key_slow_inc",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580984640,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:156",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap",
        "arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/tracepoint.c:trace_resched_ipi_reg",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_reg",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/clock.c:sched_clock_init",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "kernel/context_tracking.c:context_tracking_cpu_set",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool",
        "net/ipv4/tcp_input.c:clean_acked_data_enable",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984640,
      "name": "static_key_slow_inc",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581029760,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:156",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap",
        "arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/tracepoint.c:trace_resched_ipi_reg",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_reg",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/clock.c:sched_clock_init",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool",
        "net/ipv4/tcp_input.c:clean_acked_data_enable",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029760,
      "name": "static_key_slow_inc",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void static_key_slow_inc(struct static_key * key)
```

```json
{
  "name": "static_key_slow_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581091184,
      "name": "static_key_slow_inc",
      "external": true,
      "loc": "kernel/jump_label.c:156",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap",
        "arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/kvm.c:activate_jump_labels",
        "arch/x86/kernel/tracepoint.c:trace_resched_ipi_reg",
        "arch/x86/kernel/tracepoint.c:trace_pagefault_reg",
        "kernel/sched/core.c:preempt_notifier_inc",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/clock.c:sched_clock_init",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/events/core.c:perf_swevent_init",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_write",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg",
        "net/core/sock.c:sk_set_memalloc",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool",
        "net/ipv4/tcp_input.c:clean_acked_data_enable",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata",
        "net/ipv6/udp.c:udpv6_encap_enable",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581091184,
      "name": "static_key_slow_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
void static_key_slow_inc(struct static_key * key)
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
void static_key_slow_inc(struct static_key * key)
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
