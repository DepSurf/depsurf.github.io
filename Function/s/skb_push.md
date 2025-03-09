# Function: <code>skb_push</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned char * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586209456,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1446",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_push"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586209456,
      "name": "skb_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
unsigned char * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586646655,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1451",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_push"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586630448,
      "name": "skb_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
unsigned char * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586831145,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1451",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_push"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586815232,
      "name": "skb_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586953700,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1464",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_push"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_generic_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586943584,
      "name": "skb_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587449492,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1709",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_vlan_push"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_generic_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587437424,
      "name": "skb_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1711",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587771418,
      "name": "skb_push.cold.81",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071587735232,
      "name": "skb_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1721",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587905121,
      "name": "skb_push.cold.82",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071587869392,
      "name": "skb_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1880",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588211553,
      "name": "skb_push.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071588174672,
      "name": "skb_push",
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
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1880",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588416590,
      "name": "skb_push.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071588379808,
      "name": "skb_push",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589266947,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1879",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:skb_segment_list"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:validate_xmit_vlan",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/drop_monitor.c:net_dm_hw_packet_report",
        "net/core/drop_monitor.c:net_dm_packet_report",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_encap",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_push_rthdr4",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589284319,
      "name": "skb_push.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071589241056,
      "name": "skb_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589266257,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1890",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:skb_segment_list"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:validate_xmit_vlan",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/drop_monitor.c:net_dm_hw_packet_report",
        "net/core/drop_monitor.c:net_dm_packet_report",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_encap",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_push_rthdr4",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591627096,
      "name": "skb_push.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071589240336,
      "name": "skb_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589153939,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1932",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:skb_segment_list"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:validate_xmit_vlan",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_push_rthdr4",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591570487,
      "name": "skb_push.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589135184,
      "name": "skb_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589874211,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:2004",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:skb_segment_list"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:validate_xmit_vlan",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_push_rthdr4",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592693951,
      "name": "skb_push.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589853904,
      "name": "skb_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591406130,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:2029",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:skb_segment_list"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_encap",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_push_rthdr4",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_encap",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/mctp/route.c:mctp_local_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594578312,
      "name": "skb_push.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071591378848,
      "name": "skb_push",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593171138,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:2232",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:skb_segment_list"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/filter.c:bpf_skb_generic_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_encap",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_push_rthdr4",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_encap",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/mctp/route.c:mctp_local_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593139552,
      "name": "skb_push",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593624514,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:2396",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:skb_segment_list"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/filter.c:bpf_skb_generic_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_encap",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_push_rthdr4",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:seg6_pop_srh",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_encap",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/mctp/route.c:mctp_local_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593592240,
      "name": "skb_push",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594399842,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:2484",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:skb_segment_list"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/filter.c:bpf_skb_generic_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_encap",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_gro_udp_encap_rcv",
        "net/ipv4/xfrm4_input.c:xfrm4_gro_udp_encap_rcv",
        "net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_push_rthdr4",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/xfrm6_input.c:xfrm6_gro_udp_encap_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_gro_udp_encap_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:seg6_pop_srh",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_encap",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd",
        "net/mctp/route.c:mctp_local_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594365136,
      "name": "skb_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501890936,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1880",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501890936,
      "name": "skb_push",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234654692,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1880",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234654692,
      "name": "skb_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295303376,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1880",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295303376,
      "name": "skb_push",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278211168,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1880",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/raw.c:raw_rcv",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278211168,
      "name": "skb_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1880",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588023374,
      "name": "skb_push.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071587986592,
      "name": "skb_push",
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
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1880",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/vxlan.c:neigh_reduce",
        "drivers/net/vxlan.c:neigh_reduce",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587736462,
      "name": "skb_push.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071587699696,
      "name": "skb_push",
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
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1880",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588355150,
      "name": "skb_push.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071588318368,
      "name": "skb_push",
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
void * skb_push(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_push",
      "external": true,
      "loc": "net/core/skbuff.c:1880",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/filter.c:bpf_skb_net_hdr_push",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_header",
        "net/802/fc.c:fc_header",
        "net/802/fc.c:fc_header",
        "net/802/fddi.c:fddi_header",
        "net/802/fddi.c:fddi_header",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/ping.c:ping_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/exthdrs.c:ipv6_push_exthdr",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588490670,
      "name": "skb_push.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071588453712,
      "name": "skb_push",
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned char *</code> ➡️ <code>void *</code>
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
