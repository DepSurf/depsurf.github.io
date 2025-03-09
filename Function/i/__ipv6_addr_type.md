# Function: <code>__ipv6_addr_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587232224,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:36",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_rcv",
        "net/ipv6/udp.c:ipv6_rcv_saddr_equal",
        "net/ipv6/udp.c:ipv6_rcv_saddr_equal",
        "net/ipv6/udp.c:ipv6_rcv_saddr_equal",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/reassembly.c:ip6_frag_match",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587232224,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587696784,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:36",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/reassembly.c:ip6_frag_match",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:ipv6_rcv_saddr_equal",
        "net/ipv6/inet6_hashtables.c:ipv6_rcv_saddr_equal",
        "net/ipv6/inet6_hashtables.c:ipv6_rcv_saddr_equal",
        "net/ncsi/ncsi-manage.c:ncsi_inet6addr_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587696784,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587911136,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:36",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:addrconf_dst_alloc",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_input_lookup",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/reassembly.c:ip6_frag_match",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/inet6_hashtables.c:ipv6_rcv_saddr_equal",
        "net/ipv6/inet6_hashtables.c:ipv6_rcv_saddr_equal",
        "net/ipv6/inet6_hashtables.c:ipv6_rcv_saddr_equal",
        "net/ncsi/ncsi-manage.c:ncsi_inet6addr_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587911136,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588069488,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:36",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:addrconf_dst_alloc",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_input_lookup",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/reassembly.c:ip6_frag_match",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ncsi/ncsi-manage.c:ncsi_inet6addr_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588069488,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588613664,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:36",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_input_lookup",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/reassembly.c:ip6_frag_match",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ncsi/ncsi-manage.c:ncsi_inet6addr_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588613664,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588979600,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:36",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_input_lookup",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ncsi/ncsi-manage.c:ncsi_inet6addr_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588979600,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589203616,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:36",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_input_lookup",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ncsi/ncsi-manage.c:ncsi_inet6addr_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589203616,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589657600,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:37",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_input_lookup",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ncsi/ncsi-manage.c:ncsi_inet6addr_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589657600,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589882000,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:38",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_input_lookup",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589882000,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590910224,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:38",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward_proxy_check",
        "net/ipv6/ip6_output.c:ip6_forward_proxy_check",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifmcaddr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_sit_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_validate_gw",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590910224,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590973424,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:38",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward_proxy_check",
        "net/ipv6/ip6_output.c:ip6_forward_proxy_check",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifmcaddr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_sit_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_validate_gw",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590973424,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590904288,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:38",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_validate_gw",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_route_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590904288,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591739904,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:38",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_validate_gw",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_route_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591739904,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593444464,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:38",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_alloc",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_validate_gw",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_route_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593444464,
      "name": "__ipv6_addr_type",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595360480,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:38",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_alloc",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_validate_gw",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_route_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595360480,
      "name": "__ipv6_addr_type",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595757664,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:38",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_alloc",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_route_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595757664,
      "name": "__ipv6_addr_type",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596605840,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:38",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr",
        "net/ipv4/inet_hashtables.c:inet_bind2_bucket_create",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_check_bind_addr",
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_alloc",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_route_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596605840,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503602608,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:38",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_input_lookup",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503602608,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236247580,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:38",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_input_lookup",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_rcv",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236247580,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297414320,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:38",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_input_lookup",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297414320,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279555270,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:38",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_input_lookup",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279555270,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589486368,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:38",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_input_lookup",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589486368,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589211360,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:38",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/vxlan.c:vxlan_config_validate",
        "drivers/net/vxlan.c:vxlan_config_validate",
        "drivers/net/vxlan.c:vxlan_snoop",
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ip_tunnel.c:ip_tunnel_xmit",
        "net/ipv4/ip_tunnel.c:ip_tunnel_xmit",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_input_lookup",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589211360,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589927632,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:38",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/netfilter/nf_conntrack_proto.c:ipv6_getorigdst",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_input_lookup",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589927632,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int __ipv6_addr_type(const struct in6_addr * addr)
```

```json
{
  "name": "__ipv6_addr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589976960,
      "name": "__ipv6_addr_type",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:38",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/utils.c:inet6_pton",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/filter.c:bpf_ipv6_fib_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr_src",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_add",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_output_flags_noref",
        "net/ipv6/route.c:ip6_route_input_lookup",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_redirect_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/datagram.c:ip6_datagram_send_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589976960,
      "name": "__ipv6_addr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
