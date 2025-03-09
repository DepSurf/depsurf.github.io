# Function: <code>skb_clone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586211888,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1009",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_segment",
        "net/core/datagram.c:__skb_recv_datagram",
        "net/core/dev.c:dev_hard_start_xmit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:flush_stack",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:flush_stack",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586211888,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586638864,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1014",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586638864,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586824400,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1014",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586824400,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586948000,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1016",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586948000,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587450800,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1261",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587450800,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587754560,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1262",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587754560,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587889168,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1271",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587889168,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588194864,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1430",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588194864,
      "name": "skb_clone",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588400032,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1430",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588400032,
      "name": "skb_clone",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589260912,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1429",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:send_cpu_listeners",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:run_bpf_filter",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:__netlink_deliver_tap_skb",
        "net/netlink/genetlink.c:genlmsg_mcast",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_call_ra_chain",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589260912,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589260048,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1440",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:send_cpu_listeners",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:run_bpf_filter",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:__netlink_deliver_tap_skb",
        "net/netlink/genetlink.c:genlmsg_mcast",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_call_ra_chain",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589260048,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589152016,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1482",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:run_bpf_filter",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589152016,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589872224,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1503",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_expand_head",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:run_bpf_filter",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589872224,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591402544,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1497",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_expand_head",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591402544,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593167584,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1695",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_expand_head",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593167584,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593621856,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1847",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_expand_head",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593621856,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594397008,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1935",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_expand_head",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594397008,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501916040,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1430",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501916040,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234676608,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1430",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234676608,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295331520,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1430",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295331520,
      "name": "skb_clone",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278228236,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1430",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278228236,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588006816,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1430",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588006816,
      "name": "skb_clone",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587719904,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1430",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "drivers/net/vxlan.c:vxlan_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587719904,
      "name": "skb_clone",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588338592,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1430",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netfilter/nfnetlink.c:nfnetlink_rcv_batch",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588338592,
      "name": "skb_clone",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sk_buff * skb_clone(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588474064,
      "name": "skb_clone",
      "external": true,
      "loc": "net/core/skbuff.c:1430",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_exit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_clone_sk",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ipv4/ip_input.c:ip_call_ra_chain",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/ip6mr.c:ip6_mr_forward",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588474064,
      "name": "skb_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
