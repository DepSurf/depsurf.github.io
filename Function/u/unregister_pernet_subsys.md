# Function: <code>unregister_pernet_subsys</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586251568,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:903",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586251568,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586675840,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:903",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586675840,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586860112,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:943",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586860112,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586983552,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1009",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586983552,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587481008,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1011",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587481008,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587785504,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1071",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587785504,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587918352,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1181",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587918352,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588227392,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1268",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588227392,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588432032,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1275",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588432032,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589300384,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1273",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/sched/act_api.c:tcf_register_action",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589300384,
      "name": "unregister_pernet_subsys",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589299136,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1277",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/sched/act_api.c:tcf_register_action",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589299136,
      "name": "unregister_pernet_subsys",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589194688,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1270",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/sched/act_api.c:tcf_register_action",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589194688,
      "name": "unregister_pernet_subsys",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589916304,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1272",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/sched/act_api.c:tcf_register_action",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/ioam6.c:ioam6_exit",
        "net/ipv6/ioam6.c:ioam6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589916304,
      "name": "unregister_pernet_subsys",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591447504,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1271",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/act_api.c:tcf_register_action",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/ioam6.c:ioam6_exit",
        "net/ipv6/ioam6.c:ioam6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mctp/route.c:mctp_routes_exit",
        "net/mctp/neigh.c:mctp_neigh_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591447504,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593214944,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1291",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/ioam6.c:ioam6_exit",
        "net/ipv6/ioam6.c:ioam6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mctp/route.c:mctp_routes_exit",
        "net/mctp/neigh.c:mctp_neigh_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593214944,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593675408,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1290",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/ioam6.c:ioam6_exit",
        "net/ipv6/ioam6.c:ioam6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mctp/route.c:mctp_routes_exit",
        "net/mctp/neigh.c:mctp_neigh_exit",
        "net/handshake/netlink.c:handshake_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593675408,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594453488,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1339",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/mcast.c:igmp6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/ioam6.c:ioam6_exit",
        "net/ipv6/ioam6.c:ioam6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/devlink/core.c:devlink_init",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mctp/route.c:mctp_routes_exit",
        "net/mctp/neigh.c:mctp_neigh_exit",
        "net/handshake/netlink.c:handshake_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594453488,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501953272,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1275",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501953272,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234708948,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1275",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234708948,
      "name": "unregister_pernet_subsys",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295375952,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1275",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295375952,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278256522,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1275",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278256522,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588038816,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1275",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588038816,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587751904,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1275",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/vxlan.c:vxlan_cleanup_module",
        "drivers/net/vxlan.c:vxlan_init_module",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587751904,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588370592,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1275",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/netfilter/core.c:netfilter_init",
        "net/netfilter/nfnetlink.c:nfnetlink_exit",
        "net/netfilter/nfnetlink_queue.c:nfnetlink_queue_fini",
        "net/netfilter/nfnetlink_queue.c:nfnetlink_queue_init",
        "net/netfilter/nfnetlink_log.c:nfnetlink_log_fini",
        "net/netfilter/nfnetlink_log.c:nfnetlink_log_init",
        "net/netfilter/nf_conntrack_standalone.c:nf_conntrack_standalone_fini",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_exit",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/netfilter/nf_defrag_ipv4.c:nf_defrag_fini",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/ipv6/netfilter/nf_defrag_ipv6_hooks.c:nf_defrag_fini",
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_cleanup",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588370592,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void unregister_pernet_subsys(struct pernet_operations * ops)
```

```json
{
  "name": "unregister_pernet_subsys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588506256,
      "name": "unregister_pernet_subsys",
      "external": true,
      "loc": "net/core/net_namespace.c:1275",
      "file": "net/core/net_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/netfilter/core.c:netfilter_init",
        "net/ipv4/tcp_ipv4.c:tcp4_proc_exit",
        "net/ipv4/raw.c:raw_proc_exit",
        "net/ipv4/udp.c:udp4_proc_exit",
        "net/ipv4/igmp.c:igmp_mc_init",
        "net/ipv4/ping.c:ping_proc_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/unix/af_unix.c:af_unix_exit",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:if6_proc_exit",
        "net/ipv6/addrlabel.c:ipv6_addr_label_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ndisc.c:ndisc_cleanup",
        "net/ipv6/ndisc.c:ndisc_init",
        "net/ipv6/udplite.c:udplite6_proc_exit",
        "net/ipv6/raw.c:raw6_proc_exit",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/mcast.c:igmp6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/ping.c:pingv6_exit",
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup",
        "net/ipv6/seg6.c:seg6_exit",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_fini",
        "net/ipv6/fib6_rules.c:fib6_rules_cleanup",
        "net/ipv6/proc.c:ipv6_misc_proc_exit",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/wireless/wext-core.c:wireless_nlevent_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588506256,
      "name": "unregister_pernet_subsys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
