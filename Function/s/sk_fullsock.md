# Function: <code>sk_fullsock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585065203,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586190551,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586272797,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_pick_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586563890,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586586181,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586612036,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586668734,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586702022,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586709572,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586711243,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586737336,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586852126,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586982277,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586987473,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586989446,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:ip6_make_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587055952,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587086654,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587096036,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587110020,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587123582,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_bind",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:raw6_icmp_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587134002,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmpv6_echo_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587141715,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ipv6_sock_mc_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587166472,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587177944,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587184758,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587193457,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587197735,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587221869,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587230390,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2237",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586612695,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586698829,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_pick_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586821657,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587009825,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587029381,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587056677,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587123248,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587149590,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587157350,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587159164,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587183864,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587300662,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587428837,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/af_inet6.c:inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587435270,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587452401,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587503872,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587540510,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587546357,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587562537,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587578121,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587588228,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587594396,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587629743,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587631925,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587643760,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587650409,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587653707,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587678877,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587687481,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587693236,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2219",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580513758,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586797095,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586884492,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_pick_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587010070,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587206321,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587225323,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587252536,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587321018,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587348614,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587356278,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587358204,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587384024,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587502646,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587632229,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/af_inet6.c:inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587638646,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587655969,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587705392,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_output_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587744958,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587750853,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587766841,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587782169,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587792518,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587799388,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587834494,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587836533,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587850272,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587856953,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587860299,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587887245,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587896201,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587901988,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2286",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580545662,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586902400,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586919072,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587008990,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_pick_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587141269,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587338505,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587357443,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587384458,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587416688,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_finish_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587450784,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587481682,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587486289,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587490925,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587500345,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587518514,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587639686,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587702110,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587781541,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/af_inet6.c:inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587788102,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587805351,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587855360,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_output_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587899326,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587906581,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587924643,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587938858,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587950039,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587955980,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587991687,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587993654,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588007341,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588013507,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588016364,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588044233,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588053328,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588059796,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2313",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580623982,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587394240,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587417200,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_set_owner_w"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587507838,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_pick_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587646841,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587856185,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587877389,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587916464,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_transfer",
        "net/ipv4/tcp.c:tcp_init_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587936684,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587972128,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588003731,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588010775,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588013245,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588041368,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588164278,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588228948,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588310357,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:inet6_bind",
        "net/ipv6/af_inet6.c:inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588317046,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588334410,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588384640,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_output_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588434222,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588441541,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588459875,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588473690,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588485850,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588490812,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588528040,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588530102,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588544205,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588550403,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588553260,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588581723,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588591360,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588598052,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2327",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580752638,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587694178,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587719772,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_set_owner_w"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587811897,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587949237,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588036889,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588200917,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588222669,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588264875,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_init_transfer",
        "net/ipv4/tcp.c:tcp_init_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588285776,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588321857,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588336167,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588354410,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588362687,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588364685,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588392040,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588518998,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588583530,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588666693,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588673909,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588691752,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588771829,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_route_output_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588795630,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588802948,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588821207,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588837354,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588849060,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588853996,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588893576,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588894777,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588908291,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588914457,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588917325,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588946583,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588956592,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588964324,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2334",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580817438,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587828274,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587852844,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_set_owner_w"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587947860,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588097525,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588204966,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588385653,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588409901,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588453172,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_init_transfer",
        "net/ipv4/tcp.c:tcp_init_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588474720,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588510961,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588525458,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588544852,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588553071,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588555069,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588582442,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588649104,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588714723,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588787495,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588882565,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588890069,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588908723,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588991989,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589016510,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589025620,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589043671,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589060874,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589072446,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589078412,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589117038,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_req",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589118246,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589131859,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589138025,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589140909,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589170932,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589180608,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589188420,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2465",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580911870,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588130594,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588157052,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_set_owner_w"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588257419,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588413205,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_tcp_sock",
        "net/core/filter.c:bpf_sk_lookup",
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid",
        "net/core/filter.c:bpf_sk_fullsock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588534109,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588787942,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588813693,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588859199,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588881652,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_init_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588918295,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588936071,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588955752,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588964202,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588966157,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588993658,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589061455,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589135694,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589218903,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589323173,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589331157,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589350662,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589438837,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags_noref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589468830,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589478947,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589498646,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589516201,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589526389,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589532540,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589563228,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589571591,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589585843,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589592058,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589595117,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589623656,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589634352,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589643076,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2478",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580965166,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588335730,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588362348,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_set_owner_w"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588462571,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588618565,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_tcp_sock",
        "net/core/filter.c:bpf_sk_release",
        "net/core/filter.c:bpf_sk_lookup",
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid",
        "net/core/filter.c:bpf_sk_fullsock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588742637,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589010907,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589036989,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589082846,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589104557,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_init_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589142071,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589160249,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589180264,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589186449,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589190621,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589218189,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589285759,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589359774,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589444215,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589547413,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589555381,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589574918,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589663205,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags_noref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589692686,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589702819,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589722726,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589740297,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589750469,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589756620,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589787340,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589795975,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589810211,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589816426,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589819342,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589847784,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589858544,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589867284,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581125438,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589195186,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589219641,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_pfree",
        "net/core/sock.c:skb_set_owner_w"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589328319,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589509645,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_select_reuseport",
        "net/core/filter.c:bpf_sk_assign",
        "net/core/filter.c:bpf_sk_assign",
        "net/core/filter.c:bpf_tcp_sock",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_release",
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp",
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:_bpf_getsockopt",
        "net/core/filter.c:_bpf_getsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid",
        "net/core/filter.c:bpf_sk_fullsock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589610547,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589654437,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_lookup",
        "net/core/sock_map.c:sock_hash_lookup",
        "net/core/sock_map.c:sock_map_lookup",
        "net/core/sock_map.c:sock_map_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589971563,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589997780,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590047202,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590069493,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_ecn_create_request",
        "net/ipv4/tcp_input.c:tcp_ecn_create_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590112630,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_ecn_send_syn",
        "net/ipv4/tcp_output.c:tcp_ecn_send_syn",
        "net/ipv4/tcp_output.c:tcp_ecn_send_syn",
        "net/ipv4/tcp_output.c:tcp_ecn_send_syn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590127064,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590153037,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590160041,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590162141,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590213683,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590261007,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590344350,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590506613,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590550533,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590559605,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590579920,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_call_ra_chain",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590676741,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags_noref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590709822,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590721971,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590741354,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590758780,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590768732,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590773196,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590815636,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590818170,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590834783,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_flow_key_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590841045,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590843998,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590874842,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590885747,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590892501,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591075013,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2549",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_copy_inaddrs",
        "net/mptcp/protocol.c:mptcp_copy_inaddrs"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581159358,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589193282,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589217417,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_pfree",
        "net/core/sock.c:skb_set_owner_w"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589327650,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589494160,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skc_to_udp6_sock",
        "net/core/filter.c:bpf_skc_to_tcp_sock",
        "net/core/filter.c:bpf_skc_to_tcp6_sock",
        "net/core/filter.c:bpf_sk_lookup_assign",
        "net/core/filter.c:sk_select_reuseport",
        "net/core/filter.c:bpf_sk_assign",
        "net/core/filter.c:bpf_sk_assign",
        "net/core/filter.c:bpf_tcp_sock",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_release",
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp",
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:_bpf_getsockopt",
        "net/core/filter.c:_bpf_getsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_sk_ancestor_cgroup_id",
        "net/core/filter.c:bpf_sk_cgroup_id",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid",
        "net/core/filter.c:bpf_skb_cgroup_classid",
        "net/core/filter.c:bpf_sk_fullsock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589626275,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589677964,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_lookup",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589765041,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590012107,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590039524,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590088768,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590112780,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_ecn_create_request",
        "net/ipv4/tcp_input.c:tcp_ecn_create_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590160084,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_ecn_send_syn",
        "net/ipv4/tcp_output.c:tcp_ecn_send_syn",
        "net/ipv4/tcp_output.c:tcp_ecn_send_syn",
        "net/ipv4/tcp_output.c:tcp_ecn_send_syn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590174855,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590202093,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590209031,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590212673,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590264451,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590313967,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590397310,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590566197,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590610245,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590619541,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590640384,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_call_ra_chain",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590737125,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags_noref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590772101,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590780739,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590800298,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590818252,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590828012,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590832444,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590866933,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590878202,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590894991,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_flow_key_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590903213,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_renew",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590904558,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590936154,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590947251,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590954357,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591140501,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2570",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_copy_inaddrs",
        "net/mptcp/protocol.c:mptcp_copy_inaddrs"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581177546,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589086802,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589111449,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_pfree",
        "net/core/sock.c:skb_set_owner_w"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589223163,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589392656,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skc_to_udp6_sock",
        "net/core/filter.c:bpf_skc_to_tcp_sock",
        "net/core/filter.c:bpf_skc_to_tcp6_sock",
        "net/core/filter.c:bpf_sk_lookup_assign",
        "net/core/filter.c:sk_select_reuseport",
        "net/core/filter.c:bpf_sk_assign",
        "net/core/filter.c:bpf_sk_assign",
        "net/core/filter.c:bpf_tcp_sock",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_release",
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp",
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:_bpf_getsockopt",
        "net/core/filter.c:_bpf_getsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_sk_ancestor_cgroup_id",
        "net/core/filter.c:bpf_sk_cgroup_id",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid",
        "net/core/filter.c:bpf_skb_cgroup_classid",
        "net/core/filter.c:bpf_sk_fullsock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589515518,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589662796,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_lookup",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589668017,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589922619,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589954100,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590003443,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590031602,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590073685,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590089250,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590116250,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590123126,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590126894,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590178928,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590229807,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590311310,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590492568,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590535653,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590545013,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590566286,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590662357,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags_noref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590699109,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590707699,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590727047,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590745369,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590755204,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590759740,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590796053,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590807335,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590824339,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590832317,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590833902,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590865968,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590877216,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590884775,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591071605,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_copy_inaddrs",
        "net/mptcp/protocol.c:mptcp_copy_inaddrs",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591133536,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2606",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_event_add_subflow"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
bool sk_fullsock(const struct sock * sk)
```

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581417185,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589804610,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589830279,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_pfree",
        "net/core/sock.c:skb_set_owner_w"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589945307,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590165310,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skc_to_udp6_sock",
        "net/core/filter.c:bpf_skc_to_tcp_sock",
        "net/core/filter.c:bpf_skc_to_tcp6_sock",
        "net/core/filter.c:bpf_sk_lookup_assign",
        "net/core/filter.c:sk_select_reuseport",
        "net/core/filter.c:bpf_sk_assign",
        "net/core/filter.c:bpf_sk_assign",
        "net/core/filter.c:bpf_tcp_sock",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_release",
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp",
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:_bpf_getsockopt",
        "net/core/filter.c:_bpf_getsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_sk_ancestor_cgroup_id",
        "net/core/filter.c:bpf_sk_cgroup_id",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid",
        "net/core/filter.c:bpf_skb_cgroup_classid",
        "net/core/filter.c:bpf_sk_fullsock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590258425,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590417296,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_lookup",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590426044,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590638337,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:__nf_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590688933,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590721341,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590773960,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590801775,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    },
    {
      "addr": 18446744071590847830,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590864194,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590879495,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590899936,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590904471,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590959956,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591016109,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591103249,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591297823,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/xfrm/xfrm_output.c:ip_skb_dst_mtu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591349381,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": [
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    },
    {
      "addr": 18446744071591355941,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591377882,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591477781,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags_noref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591515029,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591524332,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591549012,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591562039,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591572162,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": [
        "net/ipv6/icmp.c:icmp6_send"
      ]
    },
    {
      "addr": 18446744071591582384,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591609653,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591625700,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591643283,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591651613,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591653243,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591696034,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591707837,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591716181,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591918021,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_copy_inaddrs",
        "net/mptcp/protocol.c:mptcp_copy_inaddrs",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591983072,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2665",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_event_add_subflow"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590780480,
      "name": "sk_fullsock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071592716073,
      "name": "sk_fullsock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071591345744,
      "name": "sk_fullsock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071592734800,
      "name": "sk_fullsock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071591566736,
      "name": "sk_fullsock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071592741078,
      "name": "sk_fullsock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
bool sk_fullsock(const struct sock * sk)
```

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581737248,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591323694,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591349785,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591479874,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591722385,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skc_to_unix_sock",
        "net/core/filter.c:bpf_skc_to_udp6_sock",
        "net/core/filter.c:bpf_skc_to_tcp_sock",
        "net/core/filter.c:bpf_skc_to_tcp6_sock",
        "net/core/filter.c:bpf_sk_lookup_assign",
        "net/core/filter.c:sk_select_reuseport",
        "net/core/filter.c:bpf_sk_assign",
        "net/core/filter.c:bpf_sk_assign",
        "net/core/filter.c:bpf_tcp_sock",
        "net/core/filter.c:bpf_sk_release",
        "net/core/filter.c:bpf_sk_lookup",
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:_bpf_getsockopt",
        "net/core/filter.c:_bpf_getsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_sk_ancestor_cgroup_id",
        "net/core/filter.c:bpf_sk_cgroup_id",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid",
        "net/core/filter.c:bpf_skb_cgroup_classid",
        "net/core/filter.c:bpf_sk_fullsock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591846632,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592014943,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_lookup",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592025019,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592262245,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:__nf_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592316706,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592350162,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592406901,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592436688,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    },
    {
      "addr": 18446744071592483911,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592501154,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592518287,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592536626,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592543867,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592602876,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592661844,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592755339,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592964587,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ]
    },
    {
      "addr": 18446744071593021781,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593028501,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593052188,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593160885,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags_noref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593200533,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593211413,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593238050,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593253068,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593263564,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": [
        "net/ipv6/icmp.c:icmp6_send"
      ]
    },
    {
      "addr": 18446744071593274176,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593318070,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_early_demux",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593319028,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593337331,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593346097,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593347965,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593393541,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593407630,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593417196,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593643125,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_copy_inaddrs",
        "net/mptcp/protocol.c:mptcp_copy_inaddrs",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593713648,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_event_add_subflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593736894,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593745959,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593747816,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2775",
      "file": "net/mptcp/bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/bpf.c:bpf_mptcp_sock_from_subflow"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592413472,
      "name": "sk_fullsock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071594602321,
      "name": "sk_fullsock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071592962064,
      "name": "sk_fullsock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071594620981,
      "name": "sk_fullsock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071593257920,
      "name": "sk_fullsock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071594627790,
      "name": "sk_fullsock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
bool sk_fullsock(const struct sock * sk)
```

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582148896,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593077950,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593118397,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593248930,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593510065,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skc_to_unix_sock",
        "net/core/filter.c:bpf_skc_to_udp6_sock",
        "net/core/filter.c:bpf_skc_to_tcp_sock",
        "net/core/filter.c:bpf_skc_to_tcp6_sock",
        "net/core/filter.c:bpf_sk_lookup_assign",
        "net/core/filter.c:sk_select_reuseport",
        "net/core/filter.c:bpf_sk_assign",
        "net/core/filter.c:bpf_sk_assign",
        "net/core/filter.c:bpf_tcp_sock",
        "net/core/filter.c:bpf_sk_release",
        "net/core/filter.c:bpf_sk_lookup",
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:bpf_sock_ops_getsockopt",
        "net/core/filter.c:bpf_sock_ops_setsockopt",
        "net/core/filter.c:bpf_sock_addr_getsockopt",
        "net/core/filter.c:bpf_sock_addr_setsockopt",
        "net/core/filter.c:bpf_sk_getsockopt",
        "net/core/filter.c:bpf_sk_setsockopt",
        "net/core/filter.c:__bpf_getsockopt",
        "net/core/filter.c:__bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_sk_ancestor_cgroup_id",
        "net/core/filter.c:bpf_sk_cgroup_id",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid",
        "net/core/filter.c:bpf_skb_cgroup_classid",
        "net/core/filter.c:bpf_sk_fullsock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593644101,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593830143,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_lookup",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593841035,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594096821,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:__nf_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594153324,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594186210,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594200828,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr",
        "net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594229729,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594290656,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    },
    {
      "addr": 18446744071594339783,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594357491,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594375951,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594394898,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594402715,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594412431,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594466536,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594526644,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594628442,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594850923,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ]
    },
    {
      "addr": 18446744071594912661,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_cleanup_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594919733,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594944524,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595058869,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags_noref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595103347,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595110277,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595138770,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595154972,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595166012,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": [
        "net/ipv6/icmp.c:icmp6_send"
      ]
    },
    {
      "addr": 18446744071595174816,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595222974,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_early_demux",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595224132,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595243123,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595252321,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595254317,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595303077,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595318030,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595328012,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595600277,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_copy_inaddrs",
        "net/mptcp/protocol.c:mptcp_copy_inaddrs",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595667350,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_event_pm_listener",
        "net/mptcp/pm_netlink.c:mptcp_event_add_subflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595670494,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595682513,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595685224,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/mptcp/bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/bpf.c:bpf_mptcp_sock_from_subflow"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594266576,
      "name": "sk_fullsock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071596337731,
      "name": "sk_fullsock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071594848128,
      "name": "sk_fullsock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071596355743,
      "name": "sk_fullsock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071595159856,
      "name": "sk_fullsock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071596361536,
      "name": "sk_fullsock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
bool sk_fullsock(const struct sock * sk)
```

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582346350,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593529358,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593571093,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593709746,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593972018,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skc_to_unix_sock",
        "net/core/filter.c:bpf_skc_to_udp6_sock",
        "net/core/filter.c:bpf_skc_to_tcp_sock",
        "net/core/filter.c:bpf_skc_to_tcp6_sock",
        "net/core/filter.c:bpf_sk_lookup_assign",
        "net/core/filter.c:sk_select_reuseport",
        "net/core/filter.c:bpf_sk_assign",
        "net/core/filter.c:bpf_sk_assign",
        "net/core/filter.c:bpf_tcp_sock",
        "net/core/filter.c:bpf_sk_release",
        "net/core/filter.c:bpf_sk_lookup",
        "net/core/filter.c:__bpf_sk_lookup",
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:bpf_sock_ops_getsockopt",
        "net/core/filter.c:bpf_sock_ops_setsockopt",
        "net/core/filter.c:bpf_sock_addr_getsockopt",
        "net/core/filter.c:bpf_sock_addr_setsockopt",
        "net/core/filter.c:bpf_sk_getsockopt",
        "net/core/filter.c:bpf_sk_setsockopt",
        "net/core/filter.c:__bpf_getsockopt",
        "net/core/filter.c:__bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_sk_ancestor_cgroup_id",
        "net/core/filter.c:bpf_sk_cgroup_id",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid",
        "net/core/filter.c:bpf_skb_cgroup_classid",
        "net/core/filter.c:bpf_sk_fullsock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594121541,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594204683,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_lookup",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594215584,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594481919,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:__nf_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594540664,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594573281,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594577283,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_reset_saddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594616929,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594676849,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    },
    {
      "addr": 18446744071594727045,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594745224,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594764253,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594784042,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594791611,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594801823,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594857931,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594918043,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595020730,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595242047,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ]
    },
    {
      "addr": 18446744071595304341,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_cleanup_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:inet_reset_saddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595311445,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595337062,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595452101,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595497283,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595504261,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595530274,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595550204,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595561404,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": [
        "net/ipv6/icmp.c:icmp6_send"
      ]
    },
    {
      "addr": 18446744071595572860,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595618938,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_early_demux",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595620100,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595638544,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595647639,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595649709,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595698097,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595713054,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595723148,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596083397,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_copy_inaddrs",
        "net/mptcp/protocol.c:mptcp_copy_inaddrs",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596176326,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_event_pm_listener",
        "net/mptcp/pm_netlink.c:mptcp_event_add_subflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596178948,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_get_sub_addrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596193361,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596196184,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2809",
      "file": "net/mptcp/bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/bpf.c:bpf_mptcp_sock_from_subflow"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594652672,
      "name": "sk_fullsock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071596867297,
      "name": "sk_fullsock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071595239328,
      "name": "sk_fullsock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071596884643,
      "name": "sk_fullsock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071595555120,
      "name": "sk_fullsock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071596890051,
      "name": "sk_fullsock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
bool sk_fullsock(const struct sock * sk)
```

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582513054,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594301198,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594343685,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594488766,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594755426,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skc_to_unix_sock",
        "net/core/filter.c:bpf_skc_to_udp6_sock",
        "net/core/filter.c:bpf_skc_to_tcp_sock",
        "net/core/filter.c:bpf_skc_to_tcp6_sock",
        "net/core/filter.c:bpf_sk_lookup_assign",
        "net/core/filter.c:sk_select_reuseport",
        "net/core/filter.c:bpf_sk_assign",
        "net/core/filter.c:bpf_tcp_sock",
        "net/core/filter.c:bpf_sk_release",
        "net/core/filter.c:bpf_sk_lookup",
        "net/core/filter.c:__bpf_sk_lookup",
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:bpf_sock_ops_getsockopt",
        "net/core/filter.c:bpf_sock_ops_setsockopt",
        "net/core/filter.c:bpf_sock_addr_getsockopt",
        "net/core/filter.c:bpf_sock_addr_setsockopt",
        "net/core/filter.c:bpf_sk_getsockopt",
        "net/core/filter.c:bpf_sk_setsockopt",
        "net/core/filter.c:__bpf_getsockopt",
        "net/core/filter.c:__bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_sk_ancestor_cgroup_id",
        "net/core/filter.c:bpf_sk_cgroup_id",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid",
        "net/core/filter.c:bpf_skb_cgroup_classid",
        "net/core/filter.c:bpf_sk_fullsock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594917125,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595002059,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_lookup",
        "net/core/sock_map.c:sock_map_update_elem",
        "net/core/sock_map.c:sock_map_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595012960,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595284126,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:__nf_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595343150,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595376435,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595380739,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_reset_saddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595419873,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595481888,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    },
    {
      "addr": 18446744071595532101,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595550968,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595570749,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:__inet_lookup_skb",
        "net/ipv4/tcp_ipv4.c:__inet_lookup_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595595410,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595603003,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595613039,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595669045,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595735122,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_listen_sk",
        "net/ipv4/af_inet.c:__inet_listen_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595833777,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595989248,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv4/tcp_ao.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ao.c:tcp_ao_get_repair",
        "net/ipv4/tcp_ao.c:tcp_ao_set_repair",
        "net/ipv4/tcp_ao.c:tcp_ao_get_sock_info",
        "net/ipv4/tcp_ao.c:tcp_ao_get_mkts",
        "net/ipv4/tcp_ao.c:tcp_ao_del_cmd",
        "net/ipv4/tcp_ao.c:tcp_ao_add_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596083417,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/xfrm/xfrm_output.c:ip_skb_dst_mtu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596145957,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_cleanup_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:inet_reset_saddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596153349,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596157589,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596294213,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596340835,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596347813,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596373874,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596392940,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596404122,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": [
        "net/ipv6/icmp.c:icmp6_send"
      ]
    },
    {
      "addr": 18446744071596416764,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596466058,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_early_demux",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:__inet6_lookup_skb",
        "net/ipv6/tcp_ipv6.c:__inet6_lookup_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596467396,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596485840,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596495095,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596497165,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596546493,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596561228,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596570972,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596983055,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sk_clone_init",
        "net/mptcp/protocol.c:mptcp_sk_clone_init",
        "net/mptcp/protocol.c:mptcp_copy_inaddrs",
        "net/mptcp/protocol.c:mptcp_copy_inaddrs",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597050894,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_event_pm_listener",
        "net/mptcp/pm_netlink.c:mptcp_event_add_subflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597054036,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_get_sub_addrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597069192,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597073944,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/mptcp/bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/bpf.c:bpf_mptcp_sock_from_subflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597116282,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2821",
      "file": "net/handshake/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/handshake/trace.c:perf_trace_tls_contenttype",
        "net/handshake/trace.c:perf_trace_handshake_alert_class",
        "net/handshake/trace.c:trace_event_raw_event_tls_contenttype",
        "net/handshake/trace.c:trace_event_raw_event_handshake_alert_class"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595456736,
      "name": "sk_fullsock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071597792239,
      "name": "sk_fullsock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071596397824,
      "name": "sk_fullsock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071597814430,
      "name": "sk_fullsock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492312732,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501829544,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501865124,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_set_owner_w"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501987036,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502166416,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_tcp_sock",
        "net/core/filter.c:bpf_sk_release",
        "net/core/filter.c:bpf_sk_lookup",
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid",
        "net/core/filter.c:bpf_sk_fullsock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502318164,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502622948,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502646624,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502698644,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502716340,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_init_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502757912,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502776480,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502798160,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502802284,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502808756,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502843384,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502914560,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503001044,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503098640,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503219964,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503228764,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503249640,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503349552,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags_noref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503385752,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503394340,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503415484,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503435196,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503445044,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503450940,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503493012,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503501548,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503515708,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503524176,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503527988,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503564060,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503575892,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503581876,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226196628,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3234611152,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234635100,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_set_owner_w"
      ],
      "caller_func": []
    },
    {
      "addr": 3234742092,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3234908952,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_tcp_sock",
        "net/core/filter.c:bpf_sk_release",
        "net/core/filter.c:bpf_sk_lookup",
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid",
        "net/core/filter.c:bpf_sk_fullsock"
      ],
      "caller_func": []
    },
    {
      "addr": 3235048076,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3235323848,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 3235350940,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3235400152,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 3235415860,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt"
      ],
      "caller_func": []
    },
    {
      "addr": 3235462376,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3235480340,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 3235501736,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3235509536,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 3235511620,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 3235551388,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 3235608464,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 3235693768,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 3235780592,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 3235889484,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 3235897268,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 3235921856,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:__ip6_append_data",
        "net/ipv6/ip6_output.c:__ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 3236015524,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags_noref"
      ],
      "caller_func": []
    },
    {
      "addr": 3236045976,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 3236056032,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3236071884,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3236093700,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 3236103436,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 3236109352,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 3236148316,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 3236153340,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3236170892,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3236177940,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 3236181164,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 3236211364,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_local_dontfrag"
      ],
      "caller_func": []
    },
    {
      "addr": 3236222992,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 3236231776,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285551324,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295233152,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295271220,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295420460,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295636680,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_tcp_sock",
        "net/core/filter.c:bpf_sk_release",
        "net/core/filter.c:bpf_sk_lookup",
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid",
        "net/core/filter.c:bpf_sk_fullsock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295818164,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296212044,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296246896,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296310628,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296342004,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_init_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296387208,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296410940,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296438500,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296445520,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296452372,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296494688,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296586076,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296693072,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296810408,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296956584,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296967564,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296993280,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297114216,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags_noref"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297155316,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297165304,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297190924,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297216288,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297228540,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297235696,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297284288,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297291520,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297310436,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297319488,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297323212,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297363408,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297379328,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297392220,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272439896,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278175912,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278195226,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_set_owner_w"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278285152,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278419444,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_tcp_sock",
        "net/core/filter.c:bpf_sk_release",
        "net/core/filter.c:bpf_sk_lookup",
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid",
        "net/core/filter.c:bpf_sk_fullsock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278537440,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278766502,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278787530,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278828072,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278848754,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_init_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278881252,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278897130,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278915740,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278920712,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278924960,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278949990,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279009938,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279079520,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279151366,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279253268,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279260290,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279278266,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279357436,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags_noref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279382548,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279388520,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279403868,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279422878,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279431308,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279436706,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279466866,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279474060,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279486736,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279492798,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279495372,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279522202,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279532248,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279536608,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580933966,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587942514,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587969132,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_set_owner_w"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588069355,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588225301,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_tcp_sock",
        "net/core/filter.c:bpf_sk_release",
        "net/core/filter.c:bpf_sk_lookup",
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid",
        "net/core/filter.c:bpf_sk_fullsock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588349373,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588617291,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588643373,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588689230,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588710941,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_init_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588748455,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588766633,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588786648,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588792833,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588797005,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588824573,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588891935,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588965950,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589048583,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589151781,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589159749,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589179286,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589267573,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags_noref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589297054,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589307187,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589327094,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589344665,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589354837,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589360988,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589391708,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589400343,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589414579,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589420794,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589423710,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589452152,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589462912,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589471652,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580880030,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587655618,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587682236,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_set_owner_w"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587782443,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587938117,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_tcp_sock",
        "net/core/filter.c:bpf_sk_release",
        "net/core/filter.c:bpf_sk_lookup",
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid",
        "net/core/filter.c:bpf_sk_fullsock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588062077,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588329275,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588355357,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588401214,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588422925,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_init_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588460407,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588478569,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588498584,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588504769,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588508941,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588536509,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588603871,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588677886,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588773623,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588876773,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588884741,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588904278,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588992565,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags_noref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589022046,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589032179,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589052086,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589069657,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589079829,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589085980,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589116700,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589125335,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589139571,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589145786,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589148702,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589177144,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589187904,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589196644,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580925214,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588274290,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588300908,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_set_owner_w"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588401131,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588557125,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_tcp_sock",
        "net/core/filter.c:bpf_sk_release",
        "net/core/filter.c:bpf_sk_lookup",
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid",
        "net/core/filter.c:bpf_sk_fullsock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588681197,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588912460,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/netfilter/nfnetlink_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588921561,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/netfilter/nfnetlink_log.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nfnetlink_log.c:__build_packet_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588955227,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/netfilter/nf_conntrack_proto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_proto.c:ipv6_getorigdst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589053467,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589079549,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589125406,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589147117,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_init_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589184631,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589202809,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589222824,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589229009,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589233181,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589260749,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589328319,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589402334,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589465016,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/netfilter/nf_defrag_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589485447,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589588645,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589596613,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589616150,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589704437,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags_noref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589733918,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589744051,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589763958,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589781529,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589791701,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589797852,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589828572,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589837207,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589851443,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589857658,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589860574,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589889016,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589899776,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589908516,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_fullsock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580985598,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588409602,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588436236,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_set_owner_w"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588537553,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588694581,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_tcp_sock",
        "net/core/filter.c:bpf_sk_release",
        "net/core/filter.c:bpf_sk_lookup",
        "net/core/filter.c:bpf_sock_ops_cb_flags_set",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_getsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_get_socket_uid",
        "net/core/filter.c:bpf_skb_ancestor_cgroup_id",
        "net/core/filter.c:bpf_skb_cgroup_id",
        "net/core/filter.c:bpf_skb_under_cgroup",
        "net/core/filter.c:bpf_get_cgroup_classid",
        "net/core/filter.c:bpf_sk_fullsock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588821085,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589092651,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_mc_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589118973,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589165230,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589186963,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_init_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589224695,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589242937,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589262952,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589269153,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589273421,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_init_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589302077,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589369535,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv4/af_inet.c:inet_listen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589445710,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/ipv4/ping.c:ping_err",
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589531687,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv4/xfrm4_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_output.c:xfrm4_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589636453,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:ipv6_opt_accepted",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_getname",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589644741,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589664486,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_push_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589754325,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:ip6_route_output_flags_noref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589784350,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589794531,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_net_init",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589814662,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_push_pending_frames",
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589832281,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:rawv6_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589842421,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589848588,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_net_init",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589879724,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589888487,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589902835,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589909050,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589912014,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/inet6_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_xmit",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589941320,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589952096,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589960932,
      "name": "sk_fullsock",
      "external": false,
      "loc": "include/net/sock.h:2499",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_sock_delattr",
        "net/ipv6/calipso.c:calipso_sock_setattr",
        "net/ipv6/calipso.c:calipso_sock_getattr",
        "net/ipv6/calipso.c:calipso_opt_update"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool sk_fullsock(const struct sock * sk)
```
</details>
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
