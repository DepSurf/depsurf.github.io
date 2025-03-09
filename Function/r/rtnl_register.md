# Function: <code>rtnl_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, rtnl_calcit_func calcit)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586362816,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:226",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586362816,
      "name": "rtnl_register",
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
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, rtnl_calcit_func calcit)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586795888,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:248",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586795888,
      "name": "rtnl_register",
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
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, rtnl_calcit_func calcit)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586982368,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:248",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586982368,
      "name": "rtnl_register",
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
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, rtnl_calcit_func calcit)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587107216,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:250",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587107216,
      "name": "rtnl_register",
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
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587608816,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:203",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587608816,
      "name": "rtnl_register",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:266",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587943874,
      "name": "rtnl_register.cold.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587942960,
      "name": "rtnl_register",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:272",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588091938,
      "name": "rtnl_register.cold.47",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071588091024,
      "name": "rtnl_register",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:267",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588407957,
      "name": "rtnl_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588406096,
      "name": "rtnl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:267",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588613422,
      "name": "rtnl_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588612480,
      "name": "rtnl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:267",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589469126,
      "name": "rtnl_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589468048,
      "name": "rtnl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:267",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591630595,
      "name": "rtnl_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589469136,
      "name": "rtnl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:267",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591574028,
      "name": "rtnl_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589367568,
      "name": "rtnl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:267",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592701771,
      "name": "rtnl_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071590098032,
      "name": "rtnl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594588318,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:304",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594588318,
      "name": "rtnl_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071591648384,
      "name": "rtnl_register",
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
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071628181017,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:305",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init"
      ],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593431536,
      "name": "rtnl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619948985,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:308",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init"
      ],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593896496,
      "name": "rtnl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622260377,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:309",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init"
      ],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594679792,
      "name": "rtnl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502158280,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:267",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502158280,
      "name": "rtnl_register",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234901232,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:267",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234901232,
      "name": "rtnl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295627920,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:267",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295627920,
      "name": "rtnl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278413160,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:267",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278413160,
      "name": "rtnl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:267",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588220158,
      "name": "rtnl_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588219216,
      "name": "rtnl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:267",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587932990,
      "name": "rtnl_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071587932048,
      "name": "rtnl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:267",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588551982,
      "name": "rtnl_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588551040,
      "name": "rtnl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_register",
      "external": true,
      "loc": "net/core/rtnetlink.c:267",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:net_ns_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/neighbour.c:neigh_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/rtnetlink.c:rtnetlink_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/core/fib_rules.c:fib_rules_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/sch_api.c:pktsched_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/sched/act_api.c:tc_action_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/fib_frontend.c:ip_fib_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/nexthop.c:nexthop_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/dcb/dcbnl.c:dcbnl_init",
        "net/dcb/dcbnl.c:dcbnl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588689454,
      "name": "rtnl_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588688512,
      "name": "rtnl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>rtnl_calcit_func calcit</code>
</li>
</ul>
</details>
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
