# Function: <code>pskb_may_pull_reason</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
enum skb_drop_reason pskb_may_pull_reason(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_may_pull_reason",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591733972,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591747892,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591837805,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594034054,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:napi_gro_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594222729,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594485157,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594888756,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
      "file": "net/ipv4/xfrm4_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595178982,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595333762,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595340526,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_redirect_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595541588,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "addr": 18446744071595576534,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "addr": 18446744071595596345,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595618804,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595746340,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595773992,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_parse_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595921685,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
      "file": "net/strparser/strparser.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/strparser/strparser.c:__strp_recv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595923425,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596216029,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2668",
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
      "addr": 18446744071595566896,
      "name": "pskb_may_pull_reason",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
enum skb_drop_reason pskb_may_pull_reason(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "pskb_may_pull_reason",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592366575,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
      "file": "drivers/net/netkit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/netkit.c:netkit_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592477752,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592493465,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592585869,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594821334,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:napi_gro_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595020089,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595287381,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595700036,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596174791,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596181246,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_redirect_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596384356,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "addr": 18446744071596419238,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "addr": 18446744071596439209,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596465924,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596622600,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_parse_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596782741,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
      "file": "net/strparser/strparser.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/strparser/strparser.c:__strp_recv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596784465,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597093885,
      "name": "pskb_may_pull_reason",
      "external": false,
      "loc": "include/linux/skbuff.h:2675",
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
      "addr": 18446744071596409744,
      "name": "pskb_may_pull_reason",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
enum skb_drop_reason pskb_may_pull_reason(struct sk_buff * skb, unsigned int len)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
