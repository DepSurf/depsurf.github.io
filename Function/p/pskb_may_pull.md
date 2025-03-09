# Function: <code>pskb_may_pull</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585096847,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586224504,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586297593,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586399092,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/core/tso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/tso.c:tso_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586447659,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586549468,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586555188,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586701902,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586722370,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586750436,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586754140,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586763367,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586770338,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/icmp.c:icmp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586790722,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586807274,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586859821,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586860666,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586874416,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586904209,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv4/xfrm4_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586906089,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586953375,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586999908,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587005911,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587121520,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587136571,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587155407,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587159398,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587169422,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587181788,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587204296,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587218657,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587236745,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587239114,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587239610,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587243805,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1851",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585491218,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586650175,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586725758,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:__skb_csum_offload_chk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586830060,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_change_proto"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586840107,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/core/tso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/tso.c:tso_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586893478,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586992764,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586998669,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587149812,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587172018,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587200829,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587204838,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587211310,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587219498,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587239182,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587256206,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587309732,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587311307,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587322640,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587350477,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv4/xfrm4_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587352345,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587399631,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587446585,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587453498,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587571856,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587590218,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587609916,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587612070,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587627876,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587638035,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587655247,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587660984,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587675629,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587702261,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587704058,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587707447,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1952",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585678834,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586834799,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586911630,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587021132,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_change_proto"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587031032,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/core/tso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/tso.c:tso_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587087606,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587188108,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587193997,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587348836,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587372098,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587401181,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587405238,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587411710,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587420045,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587439390,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587458014,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587511716,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587513307,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587525312,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587553375,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv4/xfrm4_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587555289,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587602863,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587649945,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587657066,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587775888,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587794506,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587814460,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587816630,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587832564,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587844387,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587861839,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587869448,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587884078,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587916773,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587918618,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587922103,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:1967",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585765806,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586961759,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587043898,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587147891,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_generic_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587159209,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/core/tso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/tso.c:tso_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587216272,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587320352,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587326127,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587481908,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587506541,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587537072,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587541037,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587547906,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587556581,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587580894,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587595245,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587649076,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587650800,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587663024,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587699739,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv4/xfrm4_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587701417,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587749919,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587798443,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587806461,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587930560,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587951920,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587971821,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587973893,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587989843,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588000931,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588018094,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588024488,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588041068,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588075291,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588076906,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588079863,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2006",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586201926,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587458985,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587544199,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587655347,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_generic_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587667678,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/core/tso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/tso.c:tso_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587730762,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587841002,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587846722,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588003967,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588029125,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588060247,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588064397,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588071356,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588080229,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588104824,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588119222,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588173694,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588175388,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588188650,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588226513,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv4/xfrm4_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588228233,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588278089,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588327315,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588335573,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588465704,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588487744,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588507732,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588509801,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588526079,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588537525,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588554878,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588561618,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588578358,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588608480,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:get_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588619533,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588621178,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588624279,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2093",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586458490,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587763268,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587848209,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587978637,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587994568,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/core/tso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/tso.c:tso_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588065092,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588185863,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588191336,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588213282,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588354707,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588380434,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588412697,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588416526,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588424795,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588433465,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588458899,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588470112,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588528161,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588529792,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588543728,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588581144,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv4/xfrm4_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588582862,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588633097,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588685907,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588692963,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ip6_input.c:ipv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588827958,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588850572,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588871580,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588873942,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588891279,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588901880,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588908694,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588918902,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588924824,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588943240,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588975184,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:get_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588985477,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588987174,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588991443,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2104",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586608089,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587897204,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587987008,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588130343,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588153721,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/core/tso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/tso.c:tso_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588241633,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588368686,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588376191,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588545139,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588570715,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588604291,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588609658,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588616795,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588625489,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588646421,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588664874,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588724022,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588725640,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588738445,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588785125,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv4/xfrm4_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4",
        "net/ipv4/xfrm4_policy.c:_decode_session4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588786840,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588848873,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588902988,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588912559,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589051056,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589074016,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589094969,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589096960,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589114767,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589125330,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589142336,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589152188,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589167553,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6",
        "net/ipv6/xfrm6_policy.c:_decode_session6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589198656,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:get_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589209637,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589211395,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589215101,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589249206,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2182",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pskb_may_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586860000,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588203492,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588297933,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588445143,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588474888,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/core/tso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/tso.c:tso_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588632402,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588748341,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ipv4_link_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588771390,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588777570,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588956054,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588981949,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589015916,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589021481,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589028647,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589037381,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589058784,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589077658,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589145222,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589147038,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589170381,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589218248,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589234994,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589283648,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589345446,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589354757,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589504752,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589528117,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589549132,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589552369,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589567954,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589578978,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589596457,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589606456,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589652256,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:get_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589663464,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589665386,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589669121,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589704277,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2270",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589283648,
      "name": "pskb_may_pull",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pskb_may_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587007712,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588408580,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588506271,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588650871,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588680316,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/tso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/tso.c:tso_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588854770,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588972293,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ipv4_link_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588995022,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589001170,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589180566,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589206413,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589240556,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589246041,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589253191,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589261893,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589283056,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589301818,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589369334,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589371150,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589394990,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589443544,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589460290,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589508080,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589569654,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589578861,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589728832,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589752197,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589773196,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589776401,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589792098,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589803362,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589820841,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589830568,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589876624,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:get_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589887752,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589889642,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589893345,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589928581,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589508080,
      "name": "pskb_may_pull",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587814037,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587837521,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589273396,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589339649,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_frags_skb",
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589517786,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_generic_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589738484,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589928373,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/route.c:ipv4_send_dest_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589953138,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589959260,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590151483,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590178865,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590214346,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590220452,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590227879,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590236567,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/icmp.c:icmp_socket_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590260151,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590276361,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_iphdr",
        "net/ipv4/igmp.c:ip_mc_check_iphdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590350614,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590356180,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590392558,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590430840,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590452725,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590501599,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm_parse_spi",
        "net/xfrm/xfrm_input.c:xfrm_parse_spi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590561286,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward_proxy_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590584079,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590749840,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590770706,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590792956,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590798029,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590813919,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590828482,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590845866,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590862232,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590874136,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590903104,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:get_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590917061,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590919178,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590922609,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590957125,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2307",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
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
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587872725,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587896033,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589271046,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_dec_ttl",
        "net/core/skbuff.c:skb_eth_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589341697,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_frags_skb",
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589516313,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_adjust_room",
        "net/core/filter.c:bpf_skb_generic_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589771593,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589968967,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/route.c:ipv4_send_dest_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589993938,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590000076,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590200539,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590227975,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590265114,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590272195,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590279778,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590289127,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/icmp.c:icmp_socket_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590313096,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590329305,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_iphdr",
        "net/ipv4/igmp.c:ip_mc_check_iphdr",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590407645,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590411384,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590450254,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590489000,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590511861,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590561199,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm_parse_spi",
        "net/xfrm/xfrm_input.c:xfrm_parse_spi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590621206,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward_proxy_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590644495,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590808976,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590830002,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590852252,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590857293,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590874048,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590888562,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590906596,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590923016,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590935448,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590965557,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dt4",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:get_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590980216,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590982330,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590986449,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591021733,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2328",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool pskb_may_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587751246,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587774398,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589161110,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_dec_ttl",
        "net/core/skbuff.c:skb_eth_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589275084,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589418040,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_adjust_room",
        "net/core/filter.c:bpf_skb_net_hdr_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589675187,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589883063,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/route.c:ipv4_send_dest_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589907714,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589914431,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590114718,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590142080,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590179594,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590186928,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590194466,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590204981,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/icmp.c:icmp_socket_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590228945,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590244981,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590323495,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590327430,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590375550,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590414437,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590437818,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590486543,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm_parse_spi",
        "net/xfrm/xfrm_input.c:xfrm_parse_spi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590563609,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590568869,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590735396,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590757243,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590768121,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work"
      ],
      "caller_func": [
        "net/ipv6/mcast.c:__mld_query_work"
      ]
    },
    {
      "addr": 18446744071590786416,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590803219,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590817666,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590835973,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590852502,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590864981,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590899333,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dt4",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:get_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590910925,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590912858,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590917080,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590926204,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590952329,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2344",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590759504,
      "name": "pskb_may_pull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool pskb_may_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588347227,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588370814,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589883622,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_dec_ttl",
        "net/core/skbuff.c:skb_eth_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590003868,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590143064,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_adjust_room",
        "net/core/filter.c:bpf_skb_net_hdr_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590432195,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590646903,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/route.c:ipv4_send_dest_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590673978,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590680879,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590891750,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590922384,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590960426,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590967757,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590975858,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590986860,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/icmp.c:icmp_socket_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591012225,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591028565,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591111223,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591115158,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591174750,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591212901,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591237793,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591290927,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm_parse_spi",
        "net/xfrm/xfrm_input.c:xfrm_parse_spi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591374971,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591380635,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591546948,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591574192,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591585182,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work"
      ],
      "caller_func": [
        "net/ipv6/mcast.c:__mld_query_work"
      ]
    },
    {
      "addr": 18446744071591604272,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591621443,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591636450,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591655362,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591657764,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_get_srh",
        "net/ipv6/seg6.c:seg6_get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591681382,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591695061,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591732773,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dt4",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591746589,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591748618,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591752872,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591762673,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591788649,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2373",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591576736,
      "name": "pskb_may_pull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool pskb_may_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589751205,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589772013,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591413334,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_dec_ttl",
        "net/core/skbuff.c:skb_eth_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591530057,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591699400,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_adjust_room",
        "net/core/filter.c:bpf_skb_net_hdr_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591773296,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:napi_gro_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592031970,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592271479,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/route.c:ipv4_send_dest_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592300784,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592308567,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_check_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592530019,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592562900,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592603217,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592610948,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592619617,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592631545,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/icmp.c:icmp_socket_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592659744,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592676037,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592763902,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592767668,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592815469,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592874531,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592901127,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592957567,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm_parse_spi",
        "net/xfrm/xfrm_input.c:xfrm_parse_spi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593049144,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593055289,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593245588,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593265628,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593279990,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work"
      ],
      "caller_func": [
        "net/ipv6/mcast.c:__mld_query_work"
      ]
    },
    {
      "addr": 18446744071593296601,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593317925,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_early_demux",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593330114,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593349972,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593352516,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_get_srh",
        "net/ipv6/seg6.c:seg6_get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593372968,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593392739,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593434900,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dt4",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593452251,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593454795,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593459432,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593473716,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_parse_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593498457,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593765517,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2741",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/route.c:mctp_pkttype_receive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593268768,
      "name": "pskb_may_pull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool pskb_may_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591370348,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591422477,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593178454,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_dec_ttl",
        "net/core/skbuff.c:skb_eth_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__pskb_pull_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593303568,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593504394,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:sk_skb_adjust_room",
        "net/core/filter.c:bpf_skb_generic_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593543052,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593565120,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:napi_gro_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593848297,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594106391,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/route.c:ipv4_send_dest_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594137024,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594145015,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594388193,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594422779,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594467169,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594475262,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594484577,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594497140,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/icmp.c:icmp_socket_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594525673,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594544085,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594636766,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594639778,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594692285,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594752803,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594781287,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594843295,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm_parse_spi",
        "net/xfrm/xfrm_input.c:xfrm_parse_spi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594864409,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep",
        "net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594868893,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594941392,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594947872,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595115072,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_redirect_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595146420,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595168096,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595180886,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work"
      ],
      "caller_func": [
        "net/ipv6/mcast.c:__mld_query_work"
      ]
    },
    {
      "addr": 18446744071595200617,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595222840,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_early_demux",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595235698,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595256413,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595259204,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_get_srh",
        "net/ipv6/seg6.c:seg6_get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595280952,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595302227,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595349908,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dt4",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:decap_and_validate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595370592,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595371819,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595376648,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595394180,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_parse_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595415525,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/strparser/strparser.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/strparser/strparser.c:__strp_recv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595417265,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595704413,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2624",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/route.c:mctp_pkttype_receive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595171344,
      "name": "pskb_may_pull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591733972,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591747892,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591837805,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593635926,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_dec_ttl",
        "net/core/skbuff.c:skb_eth_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__pskb_pull_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593765283,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593967755,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:sk_skb_adjust_room",
        "net/core/filter.c:bpf_skb_generic_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594012124,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594034054,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:napi_gro_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594222729,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594485157,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_ip6_check_hbh_len",
        "net/netfilter/utils.c:nf_ip6_check_hbh_len"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594493271,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/route.c:ipv4_send_dest_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594524096,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594532135,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594776520,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594812182,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594858337,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594866572,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594876049,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594888756,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/icmp.c:icmp_socket_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594917088,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594935877,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595029198,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595032210,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595084189,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595144547,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595178982,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session6",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4",
        "net/xfrm/xfrm_policy.c:decode_session4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595234606,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm_parse_spi",
        "net/xfrm/xfrm_input.c:xfrm_parse_spi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595256089,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep",
        "net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595260829,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595333762,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595340526,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595509049,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_redirect_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595541588,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595563555,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595576534,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595596345,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595618804,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_early_demux",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595631074,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595651690,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595654564,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_get_srh",
        "net/ipv6/seg6.c:seg6_get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595676744,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595697249,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595746340,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dt4",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:seg6_pop_srh",
        "net/ipv6/seg6_local.c:decap_and_validate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595767774,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595769003,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595773992,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595790244,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_parse_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595921685,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/strparser/strparser.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/strparser/strparser.c:__strp_recv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595923425,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596216029,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2682",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/route.c:mctp_pkttype_receive"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592366575,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "drivers/net/netkit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/netkit.c:netkit_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592477752,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592493465,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592585869,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594411542,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_dec_ttl",
        "net/core/skbuff.c:skb_eth_pop",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__pskb_pull_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594544424,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594752379,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:sk_skb_adjust_room",
        "net/core/filter.c:bpf_skb_generic_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594798492,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594821334,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:napi_gro_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595020089,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595287381,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/netfilter/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/utils.c:nf_ip6_check_hbh_len",
        "net/netfilter/utils.c:nf_ip6_check_hbh_len"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595296167,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/route.c:ipv4_send_dest_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595326800,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595334871,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595588031,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595623430,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595669681,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595677900,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595687345,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595700036,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/icmp.c:icmp_socket_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595729056,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595748101,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595842046,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595845058,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595896989,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595962005,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_gro_udp_encap_rcv",
        "net/ipv4/xfrm4_input.c:__xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596075086,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm_parse_spi",
        "net/xfrm/xfrm_input.c:xfrm_parse_spi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596096521,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep",
        "net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596101213,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596174791,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596181246,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596352569,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_redirect_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596384356,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596406306,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596419238,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596439209,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596465924,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_early_demux",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596478434,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596499146,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596502212,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_get_srh",
        "net/ipv6/seg6.c:seg6_get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596524565,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596545607,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_gro_udp_encap_rcv",
        "net/ipv6/xfrm6_input.c:__xfrm6_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596594516,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dt4",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:seg6_pop_srh",
        "net/ipv6/seg6_local.c:decap_and_validate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596615986,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596617227,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596622600,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg",
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596640740,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_parse_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596782741,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/strparser/strparser.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/strparser/strparser.c:__strp_recv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596784465,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597093885,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2689",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/route.c:mctp_pkttype_receive"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pskb_may_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500130052,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501925152,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502038992,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502197068,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502233948,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/tso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/tso.c:tso_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502439012,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502575124,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ipv4_link_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502599704,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502607892,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502798472,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502827408,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502867692,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502874048,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502880964,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502890640,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502912148,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502928904,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503011748,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503013272,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503052844,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503097916,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503113136,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503172096,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503243832,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503254968,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503411868,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503446780,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503474676,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503482612,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503496280,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503509032,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503529488,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503548896,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503596016,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:get_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503610008,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503611936,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503616268,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503655220,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503172096,
      "name": "pskb_may_pull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
int pskb_may_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232620356,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 3234684852,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 3234788776,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 3234948612,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 3234979732,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/tso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/tso.c:tso_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3235157416,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 3235281948,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ipv4_link_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 3235305732,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 3235313664,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235502036,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 3235528984,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 3235564048,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3235566588,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 3235576104,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235584408,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 3235605580,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 3235629324,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 3235701200,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 3235702972,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 3235737652,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 3235779912,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3235799904,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session"
      ],
      "caller_func": []
    },
    {
      "addr": 3235848888,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input"
      ]
    },
    {
      "addr": 3235913872,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 3235927352,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 3236082432,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3236105560,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 3236128396,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query"
      ],
      "caller_func": []
    },
    {
      "addr": 3236133788,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3236149748,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3236164168,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3236182260,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 3236193740,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3236241324,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:get_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 3236253864,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 3236255668,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236260084,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6"
      ],
      "caller_func": []
    },
    {
      "addr": 3236296364,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235847696,
      "name": "pskb_may_pull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
int pskb_may_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293341904,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295343316,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295485392,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295691012,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295724340,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/tso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/tso.c:tso_start"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295988288,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296162092,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ipv4_link_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296191552,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296200188,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296438964,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296478224,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296524732,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296532208,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296541196,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296552404,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296583008,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296608740,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296705064,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296706176,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296742956,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296809356,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296846072,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296898960,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296985712,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296998768,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297199392,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297230808,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297261820,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297268168,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297286964,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297301308,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297325216,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297339012,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297406140,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:get_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297422880,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297425324,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297430732,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297476736,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296898960,
      "name": "pskb_may_pull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pskb_may_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277075240,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278235808,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278326344,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278454646,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278476598,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/tso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/tso.c:tso_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278627900,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278733446,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ipv4_link_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278752202,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278757576,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278915986,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278940644,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278970908,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278975768,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278981190,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278989256,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279007960,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279026116,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279084540,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279086054,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279110306,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279150806,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279171028,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279214930,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279273232,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279281716,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279412686,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279433044,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279452724,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279457180,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279470650,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279480916,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279496368,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279506200,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279549486,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:get_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279561242,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279562820,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279567278,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279597294,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279214930,
      "name": "pskb_may_pull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pskb_may_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586764736,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588015364,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588113007,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588257607,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588287052,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/tso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/tso.c:tso_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588461154,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588578677,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ipv4_link_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588601406,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588607554,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588786950,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588812797,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588846940,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588852425,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588859384,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588868069,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588889232,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588907994,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588975510,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588977326,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589000285,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589047912,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589064658,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589112448,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589174022,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589183229,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589333200,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589356565,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589377564,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589380769,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589396466,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589407730,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589425209,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589434936,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589480992,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:get_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589492120,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589494010,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589497713,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589532949,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589112448,
      "name": "pskb_may_pull",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pskb_may_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586660070,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "drivers/net/vxlan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/vxlan.c:vxlan_xmit",
        "drivers/net/vxlan.c:vxlan_xmit",
        "drivers/net/vxlan.c:route_shortcircuit",
        "drivers/net/vxlan.c:route_shortcircuit",
        "drivers/net/vxlan.c:neigh_reduce",
        "drivers/net/vxlan.c:vxlan_err_lookup",
        "drivers/net/vxlan.c:vxlan_rcv",
        "drivers/net/vxlan.c:vxlan_rcv",
        "drivers/net/vxlan.c:vxlan_gro_receive",
        "drivers/net/vxlan.c:vxlan_gro_receive",
        "drivers/net/vxlan.c:vxlan_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586669968,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587728452,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587825839,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587970423,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587999868,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/tso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/tso.c:tso_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588173842,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588290661,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ipv4_link_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588313390,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588319538,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588498886,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588524733,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588558876,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588564361,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588571320,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588580005,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588601168,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588619930,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588687446,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588689262,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588723341,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588772952,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588789698,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588837488,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588899014,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588908221,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589058192,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589081557,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589102556,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589105761,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589121458,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589132722,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589150201,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589159928,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589205984,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:get_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589217112,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589219002,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589223777,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589259013,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588837488,
      "name": "pskb_may_pull",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pskb_may_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586962272,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588347140,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588444831,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588589431,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588618876,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/tso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/tso.c:tso_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588793330,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589014853,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ipv4_link_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589037582,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589043730,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589223126,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248973,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589283116,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589288601,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589295751,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589304453,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589325616,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589344378,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589411894,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589413710,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589436669,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589484776,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589501522,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589549312,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589610886,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589620093,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589770064,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589793429,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589814428,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589817633,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589833330,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589844594,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589862073,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589871800,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589917856,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:get_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589925425,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/netfilter/nf_conntrack_reasm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589933384,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589935274,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589938977,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589974213,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589549312,
      "name": "pskb_may_pull",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pskb_may_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_may_pull",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587070864,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588482612,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_checksum_trimmed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588581743,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:netif_skb_features",
        "net/core/dev.c:skb_network_protocol",
        "net/core/dev.c:skb_network_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588726919,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_net_hdr_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588756668,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/core/tso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/tso.c:tso_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588933984,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589053447,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/route.c:ipv4_link_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589076590,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589083218,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589263254,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589289597,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gro_receive",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589324524,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589330073,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589337255,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589346165,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589373610,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_gro_receive",
        "net/ipv4/af_inet.c:inet_gso_segment",
        "net/ipv4/af_inet.c:inet_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589386698,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:ip_mc_check_igmp",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589455382,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589457234,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589481246,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv4/ipmr.c:pim_rcv_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589531000,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589548002,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session",
        "net/xfrm/xfrm_policy.c:__xfrm_decode_session"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589596640,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589659208,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589668525,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589820768,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp_v6_early_demux",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589844133,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589865420,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589868353,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589884594,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589895874,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_parse_hopopts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589913529,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589923304,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589970464,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/ipv6/seg6_local.c:get_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589982658,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs",
        "net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589984762,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589988481,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/ipv6/mcast_snoop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590023861,
      "name": "pskb_may_pull",
      "external": false,
      "loc": "include/linux/skbuff.h:2284",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589596640,
      "name": "pskb_may_pull",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int pskb_may_pull(struct sk_buff * skb, unsigned int len)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int pskb_may_pull(struct sk_buff * skb, unsigned int len)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
bool pskb_may_pull(struct sk_buff * skb, unsigned int len)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
bool pskb_may_pull(struct sk_buff * skb, unsigned int len)
```
</details>
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
