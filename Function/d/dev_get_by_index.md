# Function: <code>dev_get_by_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586264704,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:847",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:do_sysctl",
        "security/selinux/netif.c:sel_netif_sid",
        "security/lsm_audit.c:common_lsm_audit",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586264704,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586689856,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:851",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:do_sysctl",
        "security/selinux/netif.c:sel_netif_sid",
        "security/lsm_audit.c:common_lsm_audit",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586689856,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586875808,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:850",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:do_sysctl",
        "security/selinux/netif.c:sel_netif_sid",
        "security/lsm_audit.c:common_lsm_audit",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586875808,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587000304,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:857",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netif.c:sel_netif_sid",
        "security/lsm_audit.c:common_lsm_audit",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587000304,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587498944,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:860",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_update_elem",
        "security/selinux/netif.c:sel_netif_sid",
        "security/lsm_audit.c:common_lsm_audit",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587498944,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587803632,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:860",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_update_elem",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "security/selinux/netif.c:sel_netif_sid",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/ncsi/ncsi-netlink.c:ndp_from_ifindex",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587803632,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587938880,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:862",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_update_elem",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "security/selinux/netif.c:sel_netif_sid",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/ncsi/ncsi-netlink.c:ndp_from_ifindex",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587938880,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588248288,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:858",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_update_elem",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "security/selinux/netif.c:sel_netif_sid",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/ncsi/ncsi-netlink.c:ndp_from_ifindex",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588248288,
      "name": "dev_get_by_index",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588452448,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:776",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "security/selinux/netif.c:sel_netif_sid",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/ncsi/ncsi-netlink.c:ndp_from_ifindex",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588452448,
      "name": "dev_get_by_index",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589341840,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:974",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "security/selinux/netif.c:sel_netif_sid_slow",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/ethtool/netlink.c:ethnl_parse_header_dev_get",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589341840,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589387610,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:977",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_xdp_link_attach"
      ],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "security/selinux/netif.c:sel_netif_sid_slow",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ethtool/netlink.c:ethnl_parse_header_dev_get",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589344016,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589284470,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:1025",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_xdp_link_attach"
      ],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "security/selinux/netif.c:sel_netif_sid_slow",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ethtool/netlink.c:ethnl_parse_header_dev_get",
        "net/ipv4/icmp.c:icmp_echo",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589239344,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590011814,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:901",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_xdp_link_attach"
      ],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "security/selinux/netif.c:sel_netif_sid_slow",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/core/sock.c:sock_set_timestamping",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/bpf/test_run.c:bpf_prog_test_run_xdp",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ethtool/netlink.c:ethnl_parse_header_dev_get",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589963520,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591551310,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:848",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_xdp_link_attach"
      ],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "security/selinux/netif.c:sel_netif_sid_slow",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/core/sock.c:sock_set_timestamping",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/bpf/test_run.c:bpf_prog_test_run_xdp",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ethtool/netlink.c:ethnl_parse_header_dev_get",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591502784,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593325966,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:848",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_xdp_link_attach"
      ],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "security/selinux/netif.c:sel_netif_sid_slow",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/core/sock.c:sock_set_timestamping",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/bpf/test_run.c:bpf_prog_test_run_xdp",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ethtool/netlink.c:ethnl_parse_header_dev_get",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_policy_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593273408,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593787806,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:849",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_xdp_link_attach",
        "net/core/dev.c:netdev_get_by_index"
      ],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/offload.c:bpf_prog_dev_bound_init",
        "security/selinux/netif.c:sel_netif_sid_slow",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/core/sock.c:sock_set_timestamping",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/bpf/test_run.c:bpf_prog_test_run_xdp",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_policy_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593729264,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594568481,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:866",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_xdp_link_attach",
        "net/core/dev.c:netdev_get_by_index"
      ],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/offload.c:bpf_prog_dev_bound_init",
        "security/selinux/netif.c:sel_netif_sid_slow",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/core/sock.c:sock_set_timestamping",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/bpf/test_run.c:bpf_prog_test_run_xdp",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_policy_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594508656,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502002552,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:776",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "security/selinux/netif.c:sel_netif_sid",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/ncsi/ncsi-netlink.c:ndp_from_ifindex",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502002552,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234731228,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:776",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "security/selinux/netif.c:sel_netif_sid",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/ncsi/ncsi-netlink.c:ndp_from_ifindex",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234731228,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295440128,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:776",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "security/selinux/netif.c:sel_netif_sid",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/ncsi/ncsi-netlink.c:ndp_from_ifindex",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295440128,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278275592,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:776",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "security/selinux/netif.c:sel_netif_sid",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/ncsi/ncsi-netlink.c:ndp_from_ifindex",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278275592,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588059232,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:776",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "security/selinux/netif.c:sel_netif_sid",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/ncsi/ncsi-netlink.c:ndp_from_ifindex",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588059232,
      "name": "dev_get_by_index",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587772320,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:776",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "security/selinux/netif.c:sel_netif_sid",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/ncsi/ncsi-netlink.c:ndp_from_ifindex",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587772320,
      "name": "dev_get_by_index",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588391008,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:776",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "security/selinux/netif.c:sel_netif_sid",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/ncsi/ncsi-netlink.c:ndp_from_ifindex",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588391008,
      "name": "dev_get_by_index",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct net_device * dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588531776,
      "name": "dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:776",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "security/selinux/netif.c:sel_netif_sid",
        "security/lsm_audit.c:dump_common_audit_data",
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:vif_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/ncsi/ncsi-netlink.c:ndp_from_ifindex",
        "net/xdp/xsk.c:xsk_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588531776,
      "name": "dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
