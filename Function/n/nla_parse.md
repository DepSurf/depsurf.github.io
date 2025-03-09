# Function: <code>nla_parse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy)
```

```json
{
  "name": "nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583127536,
      "name": "nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:182",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_nla_parse_ifla",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_calcit",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/sched/sch_api.c:qdisc_get_stab",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/act_api.c:find_dump_kind",
        "net/sched/act_api.c:find_dump_kind",
        "net/sched/act_api.c:find_dump_kind",
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tc_ctl_action",
        "net/sched/ematch.c:tcf_em_tree_validate",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/dcb/dcbnl.c:dcbnl_setfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_setcfg",
        "net/dcb/dcbnl.c:dcbnl_setnumtcs",
        "net/dcb/dcbnl.c:dcbnl_setpfccfg",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcb_doit",
        "net/dcb/dcbnl.c:dcbnl_ieee_del",
        "net/dcb/dcbnl.c:dcbnl_ieee_set",
        "net/dcb/dcbnl.c:dcbnl_setapp",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg",
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_getcap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583127536,
      "name": "nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy)
```

```json
{
  "name": "nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583421728,
      "name": "nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:182",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_calcit",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_nla_parse_ifla",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_get_stab",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/act_api.c:find_dump_kind",
        "net/sched/act_api.c:find_dump_kind",
        "net/sched/act_api.c:find_dump_kind",
        "net/sched/act_api.c:tc_ctl_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_init",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/ematch.c:tcf_em_tree_validate",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/dcb/dcbnl.c:dcb_doit",
        "net/dcb/dcbnl.c:dcbnl_setfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_ieee_del",
        "net/dcb/dcbnl.c:dcbnl_ieee_set",
        "net/dcb/dcbnl.c:dcbnl_bcn_setcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_setpfccfg",
        "net/dcb/dcbnl.c:dcbnl_setapp",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_setnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583421728,
      "name": "nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
int nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy)
```

```json
{
  "name": "nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583547376,
      "name": "nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:182",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_calcit",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_nla_parse_ifla",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_get_stab",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/act_api.c:find_dump_kind",
        "net/sched/act_api.c:find_dump_kind",
        "net/sched/act_api.c:find_dump_kind",
        "net/sched/act_api.c:tc_ctl_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_init",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/ematch.c:tcf_em_tree_validate",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/dcb/dcbnl.c:dcb_doit",
        "net/dcb/dcbnl.c:dcbnl_setfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_ieee_del",
        "net/dcb/dcbnl.c:dcbnl_ieee_set",
        "net/dcb/dcbnl.c:dcbnl_bcn_setcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_setpfccfg",
        "net/dcb/dcbnl.c:dcbnl_setapp",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_setnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583547376,
      "name": "nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583585040,
      "name": "nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:186",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_calcit",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_nla_parse_ifla",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_get_stab",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/act_api.c:find_dump_kind",
        "net/sched/act_api.c:find_dump_kind",
        "net/sched/act_api.c:find_dump_kind",
        "net/sched/act_api.c:tc_ctl_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_init",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/dcb/dcbnl.c:dcb_doit",
        "net/dcb/dcbnl.c:dcbnl_setfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_ieee_del",
        "net/dcb/dcbnl.c:dcbnl_ieee_set",
        "net/dcb/dcbnl.c:dcbnl_bcn_setcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_setpfccfg",
        "net/dcb/dcbnl.c:dcbnl_setapp",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_setnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583585040,
      "name": "nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583831072,
      "name": "nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:240",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_nla_parse_ifla",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_get_stab",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:find_dump_kind",
        "net/sched/act_api.c:find_dump_kind",
        "net/sched/act_api.c:tc_ctl_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_init",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state",
        "net/dcb/dcbnl.c:dcb_doit",
        "net/dcb/dcbnl.c:dcbnl_setfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_ieee_del",
        "net/dcb/dcbnl.c:dcbnl_ieee_set",
        "net/dcb/dcbnl.c:dcbnl_bcn_setcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_setpfccfg",
        "net/dcb/dcbnl.c:dcbnl_setapp",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_setnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583831072,
      "name": "nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:240",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_nla_parse_ifla",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_get_stab",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:find_dump_kind",
        "net/sched/act_api.c:find_dump_kind",
        "net/sched/act_api.c:tc_ctl_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/dcb/dcbnl.c:dcb_doit",
        "net/dcb/dcbnl.c:dcbnl_setfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_ieee_del",
        "net/dcb/dcbnl.c:dcbnl_ieee_set",
        "net/dcb/dcbnl.c:dcbnl_bcn_setcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_setpfccfg",
        "net/dcb/dcbnl.c:dcbnl_setapp",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_setnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584033039,
      "name": "nla_parse.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584032640,
      "name": "nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584115536,
      "name": "nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:435",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_valid_dump_req",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:valid_fdb_dump_legacy",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_nla_parse_ifla",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_get_stab",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:find_dump_kind",
        "net/sched/act_api.c:find_dump_kind",
        "net/sched/act_api.c:tc_ctl_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/dcb/dcbnl.c:dcb_doit",
        "net/dcb/dcbnl.c:dcbnl_setfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_ieee_del",
        "net/dcb/dcbnl.c:dcbnl_ieee_set",
        "net/dcb/dcbnl.c:dcbnl_bcn_setcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_setpfccfg",
        "net/dcb/dcbnl.c:dcbnl_setapp",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_setnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584115536,
      "name": "nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack * extack</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, struct netlink_ext_ack * extack)
```
</details>
</li>
</ul>
