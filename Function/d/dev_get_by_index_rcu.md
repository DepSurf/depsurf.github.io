# Function: <code>dev_get_by_index_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586264624,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:822",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_get_by_index",
        "net/core/dev.c:netdev_get_name"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_expire_frag_queue",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_getname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586264624,
      "name": "dev_get_by_index_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586727791,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:826",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:dev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_expire_frag_queue",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_get_saddr6",
        "net/l3mdev/l3mdev.c:l3mdev_get_rt6_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586689760,
      "name": "dev_get_by_index_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586913631,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:825",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:dev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_expire_frag_queue",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586875712,
      "name": "dev_get_by_index_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587034041,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:832",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:dev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_expire_frag_queue",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587000208,
      "name": "dev_get_by_index_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587532073,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:835",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:dev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_expire_frag_queue",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587498848,
      "name": "dev_get_by_index_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587835272,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:835",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:dev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_expire_frag_queue",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587803536,
      "name": "dev_get_by_index_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587969032,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:837",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:dev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587938784,
      "name": "dev_get_by_index_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588282524,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:833",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:dev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588248208,
      "name": "dev_get_by_index_rcu",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588488124,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:751",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:dev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588452368,
      "name": "dev_get_by_index_rcu",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589360850,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:949",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:dev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_find_open_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_measure_rcv_mss",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_lookup",
        "net/xfrm/espintcp.c:handle_esp",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589320544,
      "name": "dev_get_by_index_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589387610,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:952",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_xdp_link_attach",
        "net/core/dev.c:netdev_get_name"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_find_open_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_measure_rcv_mss",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup",
        "net/xfrm/espintcp.c:handle_esp",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589319552,
      "name": "dev_get_by_index_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589284470,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:1000",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_xdp_link_attach",
        "net/core/dev.c:netdev_get_name"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_check_mtu",
        "net/core/filter.c:bpf_skb_check_mtu",
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_find_open_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589215216,
      "name": "dev_get_by_index_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590011814,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:876",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_xdp_link_attach",
        "net/core/dev.c:netdev_get_name"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_check_mtu",
        "net/core/filter.c:bpf_skb_check_mtu",
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_find_open_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589938320,
      "name": "dev_get_by_index_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591551315,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:823",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_xdp_link_attach",
        "net/core/dev.c:netdev_get_name"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_check_mtu",
        "net/core/filter.c:bpf_skb_check_mtu",
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu",
        "net/mctp/af_mctp.c:mctp_sendmsg",
        "net/mctp/route.c:mctp_local_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591471232,
      "name": "dev_get_by_index_rcu",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593325971,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:823",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_xdp_link_attach",
        "net/core/dev.c:netdev_get_name"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_check_mtu",
        "net/core/filter.c:bpf_skb_check_mtu",
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_lookup",
        "net/xfrm/espintcp.c:handle_esp",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu",
        "net/mctp/af_mctp.c:mctp_sendmsg",
        "net/mctp/route.c:mctp_local_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593240336,
      "name": "dev_get_by_index_rcu",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593787811,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:835",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_xdp_link_attach",
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:netdev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_check_mtu",
        "net/core/filter.c:bpf_skb_check_mtu",
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup",
        "net/xfrm/espintcp.c:handle_esp",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu",
        "net/mctp/af_mctp.c:mctp_sendmsg",
        "net/mctp/route.c:mctp_local_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593701104,
      "name": "dev_get_by_index_rcu",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594568486,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:852",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_xdp_link_attach",
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:netdev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_check_mtu",
        "net/core/filter.c:bpf_skb_check_mtu",
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/netfilter/nf_queue.c:__nf_queue",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup",
        "net/ipv4/tcp_ao.c:tcp_ao_add_cmd",
        "net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching",
        "net/ipv4/tcp_ao.c:tcp_ao_connect_init",
        "net/ipv4/tcp_ao.c:tcp_ao_syncookie",
        "net/ipv4/tcp_ao.c:tcp_v4_ao_lookup",
        "net/ipv4/tcp_ao.c:tcp_v4_ao_lookup_rsk",
        "net/xfrm/espintcp.c:handle_esp",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/tcp_ao.c:tcp_v6_ao_lookup_rsk",
        "net/ipv6/tcp_ao.c:tcp_v6_ao_lookup",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu",
        "net/mctp/af_mctp.c:mctp_sendmsg",
        "net/mctp/route.c:mctp_local_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594479472,
      "name": "dev_get_by_index_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502018888,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:751",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:dev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501976688,
      "name": "dev_get_by_index_rcu",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234770616,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:751",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:dev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect_slow",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234731144,
      "name": "dev_get_by_index_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295459368,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:751",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:dev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295404640,
      "name": "dev_get_by_index_rcu",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278309774,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:751",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:dev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278275512,
      "name": "dev_get_by_index_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588094908,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:751",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:dev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588059152,
      "name": "dev_get_by_index_rcu",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587807820,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:751",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:dev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587772240,
      "name": "dev_get_by_index_rcu",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588426684,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:751",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:dev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_expire",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588390928,
      "name": "dev_get_by_index_rcu",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * dev_get_by_index_rcu(struct net * net, int ifindex)
```

```json
{
  "name": "dev_get_by_index_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588562952,
      "name": "dev_get_by_index_rcu",
      "external": true,
      "loc": "net/core/dev.c:751",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_get_name",
        "net/core/dev.c:dev_get_by_index"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/devinet.c:inet_select_addr",
        "net/ipv4/devinet.c:inetdev_by_index",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_getname",
        "net/packet/af_packet.c:packet_getname_spkt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_fib_rule_match",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588526800,
      "name": "dev_get_by_index_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
