# Function: <code>__nla_parse</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, bool strict, const struct nla_policy * policy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584115304,
      "name": "__nla_parse",
      "external": false,
      "loc": "lib/nlattr.c:394",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:nla_parse_strict",
        "lib/nlattr.c:nla_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584115248,
      "name": "__nla_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    },
    {
      "addr": 18446744071584115780,
      "name": "__nla_parse.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584303552,
      "name": "__nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:473",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_valid_dump_req",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:valid_fdb_dump_legacy",
        "net/core/rtnetlink.c:valid_fdb_dump_strict",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
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
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
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
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/ipv4/nexthop.c:nh_valid_get_del_req",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
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
      "addr": 18446744071584303552,
      "name": "__nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584438256,
      "name": "__nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:473",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_valid_dump_req",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:valid_fdb_dump_legacy",
        "net/core/rtnetlink.c:valid_fdb_dump_strict",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
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
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
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
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/ipv4/nexthop.c:nh_valid_get_del_req",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
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
      "addr": 18446744071584438256,
      "name": "__nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585002384,
      "name": "__nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:625",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_valid_dump_req",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
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
        "net/core/lwt_bpf.c:bpf_parse_prog",
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
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_init",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/genetlink.c:ctrl_dumppolicy",
        "net/ethtool/netlink.c:ethnl_default_parse",
        "net/ethtool/netlink.c:ethnl_parse_header_dev_get",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bit",
        "net/ethtool/bitset.c:ethnl_bitset_is_compact",
        "net/ethtool/strset.c:strset_parse_request",
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg",
        "net/ethtool/cabletest.c:ethnl_act_cable_test",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:rtm_to_ifaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:nh_valid_get_del_req",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req",
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
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/mptcp/pm_netlink.c:mptcp_pm_parse_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585002384,
      "name": "__nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585123232,
      "name": "__nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:680",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_valid_dump_req",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
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
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_nla_parse_ifla",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit",
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
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_init",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/ethtool/netlink.c:ethnl_parse_header_dev_get",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bit",
        "net/ethtool/bitset.c:ethnl_bitset_is_compact",
        "net/ethtool/strset.c:strset_parse_request",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:rtm_to_ifaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:nh_valid_get_del_req",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req",
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
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/mptcp/pm_netlink.c:mptcp_pm_parse_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585123232,
      "name": "__nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585003792,
      "name": "__nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:680",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_valid_dump_req",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
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
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_nla_parse_ifla",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/core/devlink.c:devlink_port_function_set",
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
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_init",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/ethtool/netlink.c:ethnl_parse_header_dev_get",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bit",
        "net/ethtool/bitset.c:ethnl_bitset_is_compact",
        "net/ethtool/strset.c:strset_parse_request",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:rtm_to_ifaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:nh_valid_get_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_get_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_dump_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_dump_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_dump_req",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state",
        "net/ipv6/seg6_local.c:parse_nla_counters",
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
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/mptcp/pm_netlink.c:mptcp_pm_parse_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585003792,
      "name": "__nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585445200,
      "name": "__nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:680",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_valid_dump_req",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
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
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_nla_parse_ifla",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/core/devlink.c:devlink_port_function_set",
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
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_init",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/ethtool/netlink.c:ethnl_parse_header_dev_get",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bit",
        "net/ethtool/bitset.c:ethnl_bitset_is_compact",
        "net/ethtool/strset.c:strset_parse_request",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:rtm_to_ifaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:nh_valid_get_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_get_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_dump_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_dump_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_dump_req",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_valid_dump_ifaddr_req",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state",
        "net/ipv6/seg6_local.c:parse_nla_counters",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/ipv6/ioam6_iptunnel.c:ioam6_build_state",
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
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/mptcp/pm_netlink.c:mptcp_pm_parse_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585445200,
      "name": "__nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586586528,
      "name": "__nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:680",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_valid_dump_req",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_stats_set",
        "net/core/rtnetlink.c:rtnl_stats_get_parse",
        "net/core/rtnetlink.c:rtnl_stats_get_parse",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
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
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_nla_parse_ifla",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/core/devlink.c:devlink_port_function_set",
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
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_init",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/sched/ematch.c:tcf_em_tree_validate",
        "net/ethtool/netlink.c:ethnl_parse_header_dev_get",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_update_bitset32",
        "net/ethtool/bitset.c:ethnl_parse_bit",
        "net/ethtool/bitset.c:ethnl_bitset_is_compact",
        "net/ethtool/strset.c:strset_parse_request",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:nh_valid_get_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_get_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_dump_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_dump_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_dump_req",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state",
        "net/ipv6/seg6_local.c:parse_nla_counters",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/ipv6/ioam6_iptunnel.c:ioam6_build_state",
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
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr",
        "net/mctp/device.c:mctp_set_link_af",
        "net/mctp/device.c:mctp_rtm_deladdr",
        "net/mctp/device.c:mctp_rtm_newaddr",
        "net/mctp/route.c:mctp_newroute",
        "net/mctp/neigh.c:mctp_rtm_delneigh",
        "net/mctp/neigh.c:mctp_rtm_newneigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586586528,
      "name": "__nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587827056,
      "name": "__nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:695",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_valid_dump_req",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_stats_set",
        "net/core/rtnetlink.c:rtnl_stats_get_parse",
        "net/core/rtnetlink.c:rtnl_stats_get_parse",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
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
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_nla_parse_ifla",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/core/devlink.c:devlink_nl_cmd_selftests_run",
        "net/core/devlink.c:devlink_port_function_set",
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
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_init",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/sched/ematch.c:tcf_em_tree_validate",
        "net/ethtool/netlink.c:ethnl_parse_header_dev_get",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_update_bitset32",
        "net/ethtool/bitset.c:ethnl_parse_bit",
        "net/ethtool/bitset.c:ethnl_bitset_is_compact",
        "net/ethtool/strset.c:strset_parse_request",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve",
        "net/ipv4/nexthop.c:nh_valid_get_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_get_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_dump_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_dump_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_dump_req",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/ip6mr.c:ip6mr_rtm_getroute",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state",
        "net/ipv6/seg6_local.c:parse_nla_flavors",
        "net/ipv6/seg6_local.c:parse_nla_counters",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/ipv6/ioam6_iptunnel.c:ioam6_build_state",
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
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr",
        "net/mctp/device.c:mctp_set_link_af",
        "net/mctp/device.c:mctp_rtm_deladdr",
        "net/mctp/device.c:mctp_rtm_newaddr",
        "net/mctp/route.c:mctp_newroute",
        "net/mctp/neigh.c:mctp_rtm_delneigh",
        "net/mctp/neigh.c:mctp_rtm_newneigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587827056,
      "name": "__nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588098416,
      "name": "__nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:695",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_valid_dump_req",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_mdb_del",
        "net/core/rtnetlink.c:rtnl_mdb_add",
        "net/core/rtnetlink.c:rtnl_stats_set",
        "net/core/rtnetlink.c:rtnl_stats_get_parse",
        "net/core/rtnetlink.c:rtnl_stats_get_parse",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
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
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
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
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_init",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/sched/ematch.c:tcf_em_tree_validate",
        "net/ethtool/netlink.c:ethnl_parse_header_dev_get",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_update_bitset32",
        "net/ethtool/bitset.c:ethnl_parse_bit",
        "net/ethtool/bitset.c:ethnl_bitset_is_compact",
        "net/ethtool/strset.c:strset_parse_request",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve",
        "net/ipv4/nexthop.c:nh_valid_get_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_get_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_dump_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_dump_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_dump_req",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/ip6mr.c:ip6mr_rtm_getroute",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state",
        "net/ipv6/seg6_local.c:parse_nla_flavors",
        "net/ipv6/seg6_local.c:parse_nla_counters",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/ipv6/ioam6_iptunnel.c:ioam6_build_state",
        "net/devlink/leftover.c:devlink_port_function_set",
        "net/devlink/dev.c:devlink_nl_cmd_selftests_run",
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
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr",
        "net/mctp/device.c:mctp_set_link_af",
        "net/mctp/device.c:mctp_rtm_deladdr",
        "net/mctp/device.c:mctp_rtm_newaddr",
        "net/mctp/route.c:mctp_newroute",
        "net/mctp/neigh.c:mctp_rtm_delneigh",
        "net/mctp/neigh.c:mctp_rtm_newneigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588098416,
      "name": "__nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588434512,
      "name": "__nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:727",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dpll/dpll_netlink.c:dpll_pin_parent_pin_set",
        "drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_valid_dump_req",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_mdb_del",
        "net/core/rtnetlink.c:rtnl_mdb_del",
        "net/core/rtnetlink.c:rtnl_mdb_add",
        "net/core/rtnetlink.c:rtnl_mdb_get",
        "net/core/rtnetlink.c:rtnl_stats_set",
        "net/core/rtnetlink.c:rtnl_stats_get_parse",
        "net/core/rtnetlink.c:rtnl_stats_get_parse",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
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
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/page_pool_user.c:netdev_nl_page_pool_stats_get_doit",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_parse_prog",
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
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_init",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/sched/ematch.c:tcf_em_tree_validate",
        "net/ethtool/netlink.c:ethnl_parse_header_dev_get",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_update_bitset32",
        "net/ethtool/bitset.c:ethnl_parse_bit",
        "net/ethtool/bitset.c:ethnl_bitset_is_compact",
        "net/ethtool/strset.c:strset_parse_request",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve",
        "net/ipv4/nexthop.c:nh_valid_get_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_get_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_dump_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_dump_bucket_req",
        "net/ipv4/nexthop.c:nh_valid_dump_req",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/ip6mr.c:ip6mr_rtm_getroute",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:seg6_local_build_state",
        "net/ipv6/seg6_local.c:parse_nla_flavors",
        "net/ipv6/seg6_local.c:parse_nla_counters",
        "net/ipv6/seg6_local.c:parse_nla_bpf",
        "net/ipv6/ioam6_iptunnel.c:ioam6_build_state",
        "net/devlink/dev.c:devlink_nl_selftests_run_doit",
        "net/devlink/port.c:devlink_port_function_set",
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
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr",
        "net/mctp/device.c:mctp_set_link_af",
        "net/mctp/device.c:mctp_rtm_deladdr",
        "net/mctp/device.c:mctp_rtm_newaddr",
        "net/mctp/route.c:mctp_newroute",
        "net/mctp/neigh.c:mctp_rtm_delneigh",
        "net/mctp/neigh.c:mctp_rtm_newneigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588434512,
      "name": "__nla_parse",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496323608,
      "name": "__nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:473",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:valid_fdb_dump_legacy",
        "net/core/rtnetlink.c:valid_fdb_dump_strict",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
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
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
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
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/ipv4/nexthop.c:nh_valid_get_del_req",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
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
      "addr": 18446603336496323608,
      "name": "__nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229658376,
      "name": "__nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:473",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:valid_fdb_dump_legacy",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_calcit",
        "net/core/rtnetlink.c:rtnl_getlink",
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
        "net/core/rtnetlink.c:linkinfo_to_kind_ops",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_parse_prog",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
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
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_init",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/ipv4/nexthop.c:nh_valid_get_del_req",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
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
      "addr": 3229658376,
      "name": "__nla_parse",
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
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290641904,
      "name": "__nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:473",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:valid_fdb_dump_legacy",
        "net/core/rtnetlink.c:valid_fdb_dump_strict",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
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
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
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
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/ipv4/nexthop.c:nh_valid_get_del_req",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
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
      "addr": 13835058055290641904,
      "name": "__nla_parse",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275375388,
      "name": "__nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:473",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:valid_fdb_dump_legacy",
        "net/core/rtnetlink.c:valid_fdb_dump_strict",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
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
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
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
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/ipv4/nexthop.c:nh_valid_get_del_req",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
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
      "addr": 18446743936275375388,
      "name": "__nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584406992,
      "name": "__nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:473",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_valid_dump_req",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:valid_fdb_dump_legacy",
        "net/core/rtnetlink.c:valid_fdb_dump_strict",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
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
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
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
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/ipv4/nexthop.c:nh_valid_get_del_req",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
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
      "addr": 18446744071584406992,
      "name": "__nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584342192,
      "name": "__nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:473",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_valid_dump_req",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:valid_fdb_dump_legacy",
        "net/core/rtnetlink.c:valid_fdb_dump_strict",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
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
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
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
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/ipv4/nexthop.c:nh_valid_get_del_req",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
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
      "addr": 18446744071584342192,
      "name": "__nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584389904,
      "name": "__nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:473",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_valid_dump_req",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:valid_fdb_dump_legacy",
        "net/core/rtnetlink.c:valid_fdb_dump_strict",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
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
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
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
        "net/netfilter/nfnetlink.c:nfnetlink_rcv",
        "net/netfilter/nfnetlink.c:nfnetlink_rcv_batch",
        "net/netfilter/nfnetlink.c:nfnetlink_rcv_msg",
        "net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict",
        "net/netfilter/nf_conntrack_proto_tcp.c:nlattr_to_tcp",
        "net/netfilter/nf_conntrack_proto_dccp.c:nlattr_to_dccp",
        "net/netfilter/nf_conntrack_proto_sctp.c:nlattr_to_sctp",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_attach_expect",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_parse",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_synproxy",
        "net/netfilter/nf_conntrack_netlink.c:change_seq_adj",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_protoinfo",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple_proto",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/ipv4/nexthop.c:nh_valid_get_del_req",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
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
      "addr": 18446744071584389904,
      "name": "__nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584495968,
      "name": "__nla_parse",
      "external": true,
      "loc": "lib/nlattr.c:473",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/neighbour.c:neigh_valid_dump_req",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_add",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:valid_fdb_dump_legacy",
        "net/core/rtnetlink.c:valid_fdb_dump_strict",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
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
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
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
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inet_validate_link_af",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/ipv4/nexthop.c:nh_valid_get_del_req",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_validate_link_af",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_deladdr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
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
      "addr": 18446744071584495968,
      "name": "__nla_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __nla_parse(struct nlattr * * tb, int maxtype, const struct nlattr * head, int len, bool strict, const struct nla_policy * policy, struct netlink_ext_ack * extack)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int validate</code>
</li>
<li>
<b>Param removed. </b>
<code>bool strict</code>
</li>
<li>
<b>Param reordered. </b>
<code>tb, maxtype, head, len, strict, policy, extack</code> ➡️ <code>tb, maxtype, head, len, policy, validate, extack</code>
</li>
</ul>
</details>
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
