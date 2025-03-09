# Function: <code>register_pernet_subsys</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586252976,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:884",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_net.c:proc_net_init",
        "lib/kobject_uevent.c:kobject_uevent_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586252976,
      "name": "register_pernet_subsys",
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
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586677232,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:884",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_net.c:proc_net_init",
        "lib/kobject_uevent.c:kobject_uevent_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586677232,
      "name": "register_pernet_subsys",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586861888,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:924",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_net.c:proc_net_init",
        "lib/kobject_uevent.c:kobject_uevent_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586861888,
      "name": "register_pernet_subsys",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586985392,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:990",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_net.c:proc_net_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/sysctl_net.c:net_sysctl_init",
        "lib/kobject_uevent.c:kobject_uevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586985392,
      "name": "register_pernet_subsys",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587483904,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:992",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_net.c:proc_net_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/sysctl_net.c:net_sysctl_init",
        "lib/kobject_uevent.c:kobject_uevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587483904,
      "name": "register_pernet_subsys",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587789232,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1052",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "lib/kobject_uevent.c:kobject_uevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587789232,
      "name": "register_pernet_subsys",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587922464,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1162",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "lib/kobject_uevent.c:kobject_uevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587922464,
      "name": "register_pernet_subsys",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588229728,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1249",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "net/xdp/xsk.c:xsk_init",
        "lib/kobject_uevent.c:kobject_uevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588229728,
      "name": "register_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588434368,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1256",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "net/xdp/xsk.c:xsk_init",
        "lib/kobject_uevent.c:kobject_uevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588434368,
      "name": "register_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589304400,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1254",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/bpf/net_namespace.c:netns_bpf_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "security/apparmor/lsm.c:apparmor_nf_ip_init",
        "lib/kobject_uevent.c:kobject_uevent_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/devlink.c:devlink_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tcf_register_action",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mptcp/ctrl.c:mptcp_init",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589304400,
      "name": "register_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589302416,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1258",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/bpf/net_namespace.c:netns_bpf_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "security/apparmor/lsm.c:apparmor_nf_ip_init",
        "lib/kobject_uevent.c:kobject_uevent_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/devlink.c:devlink_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tcf_register_action",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mptcp/ctrl.c:mptcp_init",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589302416,
      "name": "register_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589192096,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1251",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/bpf/net_namespace.c:netns_bpf_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "security/apparmor/lsm.c:apparmor_nf_ip_init",
        "lib/kobject_uevent.c:kobject_uevent_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/devlink.c:devlink_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tcf_register_action",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mptcp/ctrl.c:mptcp_init",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589192096,
      "name": "register_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589915312,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1253",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/bpf/net_namespace.c:netns_bpf_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "security/apparmor/lsm.c:apparmor_nf_ip_init",
        "lib/kobject_uevent.c:kobject_uevent_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/devlink.c:devlink_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tcf_register_action",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/ioam6.c:ioam6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mptcp/ctrl.c:mptcp_init",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589915312,
      "name": "register_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591447008,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1252",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/bpf/net_namespace.c:netns_bpf_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "security/apparmor/lsm.c:apparmor_nf_ip_init",
        "lib/kobject_uevent.c:kobject_uevent_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/devlink.c:devlink_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tcf_register_action",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/ioam6.c:ioam6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mptcp/ctrl.c:mptcp_init",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_init",
        "net/mctp/route.c:mctp_routes_init",
        "net/mctp/neigh.c:mctp_neigh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591447008,
      "name": "register_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071628179311,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1272",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init"
      ],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/bpf/net_namespace.c:netns_bpf_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "security/apparmor/lsm.c:apparmor_nf_ip_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/devlink.c:devlink_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/ioam6.c:ioam6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mptcp/ctrl.c:mptcp_init",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_init",
        "net/mctp/route.c:mctp_routes_init",
        "net/mctp/neigh.c:mctp_neigh_init",
        "lib/kobject_uevent.c:kobject_uevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593213712,
      "name": "register_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619947279,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1271",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init"
      ],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/bpf/net_namespace.c:netns_bpf_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "security/apparmor/lsm.c:apparmor_nf_ip_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/ioam6.c:ioam6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/devlink/core.c:devlink_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mptcp/ctrl.c:mptcp_init",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_init",
        "net/mctp/route.c:mctp_routes_init",
        "net/mctp/neigh.c:mctp_neigh_init",
        "net/handshake/netlink.c:handshake_init",
        "lib/kobject_uevent.c:kobject_uevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593674176,
      "name": "register_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622258655,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1320",
      "file": "net/core/net_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init"
      ],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/bpf/net_namespace.c:netns_bpf_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "security/apparmor/lsm.c:apparmor_nf_ip_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/ioam6.c:ioam6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/devlink/core.c:devlink_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mptcp/ctrl.c:mptcp_init",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_init",
        "net/mctp/route.c:mctp_routes_init",
        "net/mctp/neigh.c:mctp_neigh_init",
        "net/handshake/netlink.c:handshake_init",
        "lib/kobject_uevent.c:kobject_uevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594452944,
      "name": "register_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501955832,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1256",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "net/xdp/xsk.c:xsk_init",
        "lib/kobject_uevent.c:kobject_uevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501955832,
      "name": "register_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234713540,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1256",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "net/xdp/xsk.c:xsk_init",
        "lib/kobject_uevent.c:kobject_uevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234713540,
      "name": "register_pernet_subsys",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295381856,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1256",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "net/xdp/xsk.c:xsk_init",
        "lib/kobject_uevent.c:kobject_uevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295381856,
      "name": "register_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278260544,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1256",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "net/xdp/xsk.c:xsk_init",
        "lib/kobject_uevent.c:kobject_uevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278260544,
      "name": "register_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588041152,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1256",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "net/xdp/xsk.c:xsk_init",
        "lib/kobject_uevent.c:kobject_uevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588041152,
      "name": "register_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587754240,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1256",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "drivers/net/vxlan.c:vxlan_init_module",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "net/xdp/xsk.c:xsk_init",
        "lib/kobject_uevent.c:kobject_uevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587754240,
      "name": "register_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588372928,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1256",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/netfilter/nfnetlink.c:nfnetlink_init",
        "net/netfilter/nfnetlink_queue.c:nfnetlink_queue_init",
        "net/netfilter/nfnetlink_log.c:nfnetlink_log_init",
        "net/netfilter/nf_conntrack_standalone.c:nf_conntrack_standalone_init",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/netfilter/nf_defrag_ipv4.c:nf_defrag_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/ipv6/netfilter/nf_defrag_ipv6_hooks.c:nf_defrag_init",
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_init",
        "net/packet/af_packet.c:packet_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "net/xdp/xsk.c:xsk_init",
        "lib/kobject_uevent.c:kobject_uevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588372928,
      "name": "register_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int register_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "register_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588508608,
      "name": "register_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1256",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "fs/proc/proc_net.c:proc_net_init",
        "security/selinux/hooks.c:selinux_nf_ip_init",
        "security/smack/smack_netfilter.c:smack_nf_ip_init",
        "net/core/sock.c:proto_init",
        "net/core/sock.c:net_inuse_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_defaults_init",
        "net/core/sysctl_net_core.c:sysctl_core_init",
        "net/core/dev.c:net_dev_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/core/fib_notifier.c:fib_notifier_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/net-procfs.c:dev_proc_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/genetlink.c:genl_init",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nf_log.c:netfilter_log_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipfrag_init",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv4/raw.c:raw_init",
        "net/ipv4/raw.c:raw_proc_init",
        "net/ipv4/udp.c:udp_init",
        "net/ipv4/udp.c:udp4_proc_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/arp.c:arp_init",
        "net/ipv4/icmp.c:icmp_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ping.c:ping_proc_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init",
        "net/ipv4/proc.c:ip_misc_proc_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_init",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_init",
        "net/ipv6/raw.c:raw6_proc_init",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_init",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_init",
        "net/ipv6/fib6_rules.c:fib6_rules_init",
        "net/ipv6/proc.c:ipv6_misc_proc_init",
        "net/packet/af_packet.c:packet_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/sysctl_net.c:net_sysctl_init",
        "net/xdp/xsk.c:xsk_init",
        "lib/kobject_uevent.c:kobject_uevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588508608,
      "name": "register_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
