# Function: <code>csum_partial</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582999449,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:133",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ],
      "caller_func": [
        "net/core/skbuff.c:csum_partial_ext",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582999488,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583289193,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:133",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:csum_partial_ext",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583289232,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583407881,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:133",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:csum_partial_ext",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407840,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588264537,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:133",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:csum_partial_ext",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_skb_generic_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588264496,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588817065,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:134",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:csum_partial_ext",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_skb_generic_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_ipv4.c:__tcp_v4_send_check",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588817024,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589195221,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:134",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:csum_partial_ext",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589195184,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589436677,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:134",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:csum_partial_ext",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589436640,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589894693,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:134",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_mod_eth_type",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589894656,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590120645,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:134",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_mod_eth_type",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590120608,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585124629,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:134",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_generic_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/unix/af_unix.c:unix_autobind",
        "net/unix/af_unix.c:unix_mkname",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:seg6_update_csum",
        "net/ipv6/exthdrs.c:seg6_update_csum",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585124592,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585275669,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:134",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_generic_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/unix/af_unix.c:unix_autobind",
        "net/unix/af_unix.c:unix_mkname",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:seg6_update_csum",
        "net/ipv6/exthdrs.c:seg6_update_csum",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585275632,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585159205,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:134",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/unix/af_unix.c:unix_autobind",
        "net/unix/af_unix.c:unix_mkname",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585159168,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585612053,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:134",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_pull_rcsum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/unix/af_unix.c:unix_mkname",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive",
        "net/mptcp/subflow.c:validate_data_csum",
        "net/mptcp/options.c:mptcp_write_options",
        "net/mptcp/options.c:mptcp_write_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585612016,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586768464,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:35",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum",
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_pull_rcsum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/unix/af_unix.c:unix_bind",
        "net/unix/af_unix.c:unix_autobind",
        "net/unix/af_unix.c:unix_find_other",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_encap",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive",
        "net/mptcp/options.c:mptcp_write_options",
        "net/mptcp/options.c:mptcp_write_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586768464,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595933520,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:35",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_pull_rcsum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_generic_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/unix/af_unix.c:unix_bind",
        "net/unix/af_unix.c:unix_autobind",
        "net/unix/af_unix.c:unix_find_other",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_encap",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive",
        "net/mptcp/options.c:mptcp_write_options",
        "net/mptcp/options.c:mptcp_write_options",
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595933520,
      "name": "csum_partial",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596451776,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:47",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "net/core/skbuff.c:skb_splice_from_iter",
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_pull_rcsum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_generic_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:__bpf_skb_store_bytes",
        "net/core/filter.c:__bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/unix/af_unix.c:unix_bind",
        "net/unix/af_unix.c:unix_autobind",
        "net/unix/af_unix.c:unix_find_other",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:seg6_pop_srh",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_encap",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive",
        "net/mptcp/options.c:mptcp_write_options",
        "net/mptcp/options.c:mptcp_write_options",
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596451776,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597347008,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:44",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/netkit.c:netkit_xmit",
        "net/core/skbuff.c:skb_splice_from_iter",
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_pull_rcsum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:csum_and_copy_to_iter",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_generic_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:__bpf_skb_store_bytes",
        "net/core/filter.c:__bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/unix/af_unix.c:unix_bind",
        "net/unix/af_unix.c:unix_autobind",
        "net/unix/af_unix.c:unix_find_other",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:seg6_pop_srh",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_encap",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive",
        "net/mptcp/options.c:mptcp_write_options",
        "net/mptcp/options.c:mptcp_write_options",
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597347008,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
__wsum csum_partial(const void * buff, int len, __wsum wsum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496325368,
      "name": "csum_partial",
      "external": true,
      "loc": "lib/checksum.c:125",
      "file": "lib/checksum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/checksum.c:csum_partial_copy",
        "lib/checksum.c:csum_partial_copy_from_user"
      ],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_mod_eth_type",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:csum_partial_ext",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496325224,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "csum_partial",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "block/t10-pi.c:t10_pi_ip_fn",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_mod_eth_type",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:csum_partial_ext",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmpv3_sendpack",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/unix/af_unix.c:unix_autobind",
        "net/unix/af_unix.c:unix_mkname",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236415824,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "csum_partial",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282859768,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "arch/powerpc/lib/checksum_wrappers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_to_user",
        "arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290282924,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_ip_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295343088,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mod_eth_type",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_pull_rcsum",
        "net/core/skbuff.c:csum_partial_ext"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295358432,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295431892,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_forward_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295633096,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/core/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295679224,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295787600,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295866340,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295988148,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ethernet/eth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:eth_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296226648,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296476188,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv4/tcp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296512456,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_set_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296531468,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv4/udp_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296605820,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmpv3_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296695056,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296706512,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv4/gre_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296743052,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:pim_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296940852,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_autobind"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296998316,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297166796,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297196648,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297220392,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297224756,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297241792,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297266176,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297286284,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297298984,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297349736,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297362224,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297395756,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297403712,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:decap_and_validate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297417036,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv6/ip6_checksum.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_checksum.c:udp6_set_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297422992,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv6/ip6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_offload.c:ipv6_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
      "file": "net/ipv6/tcpv6_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297477128,
      "name": "csum_partial",
      "external": false,
      "loc": "arch/powerpc/include/asm/checksum.h:167",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
__wsum csum_partial(const void * buff, int len, __wsum wsum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275377286,
      "name": "csum_partial",
      "external": true,
      "loc": "lib/checksum.c:125",
      "file": "lib/checksum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/checksum.c:csum_partial_copy",
        "lib/checksum.c:csum_partial_copy_from_user"
      ],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_mod_eth_type",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:csum_partial_ext",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/unix/af_unix.c:unix_autobind",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275376994,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589722901,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:134",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_mod_eth_type",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589722864,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589448677,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:134",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ],
      "caller_func": [
        "drivers/net/vxlan.c:neigh_reduce",
        "drivers/net/vxlan.c:vxlan_rcv",
        "drivers/net/vxlan.c:vxlan_rcv",
        "drivers/net/vxlan.c:vxlan_rcv",
        "drivers/net/vxlan.c:vxlan_gro_receive",
        "drivers/net/vxlan.c:vxlan_gro_receive",
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_mod_eth_type",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ip_tunnel.c:ip_tunnel_rcv",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589448640,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590166277,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:134",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_mod_eth_type",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue",
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590166240,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
__wsum csum_partial(const void * buff, int len, __wsum sum)
```

```json
{
  "name": "csum_partial",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590216789,
      "name": "csum_partial",
      "external": true,
      "loc": "arch/x86/lib/csum-partial_64.c:134",
      "file": "arch/x86/lib/csum-partial_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/csum-partial_64.c:ip_compute_csum"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_mpls_update_lse",
        "net/core/skbuff.c:skb_mpls_pop",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_mod_eth_type",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:__skb_vlan_pop",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/utils.c:inet_proto_csum_replace16",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_skb_net_hdr_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_pop",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:bpf_skb_vlan_push",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/ethernet/eth.c:eth_gro_receive",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/tcp_offload.c:tcp_gso_segment",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:udp_gro_receive",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv4/gre_offload.c:gre_gro_receive",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/icmp.c:icmpv6_push_pending_frames",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_check",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/ip6_offload.c:ipv6_gro_receive",
        "net/8021q/vlan_core.c:vlan_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590216752,
      "name": "csum_partial",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>__wsum wsum</code>
</li>
<li>
<b>Param removed. </b>
<code>__wsum sum</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
__wsum csum_partial(const void * buff, int len, __wsum sum)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
__wsum csum_partial(const void * buff, int len, __wsum sum)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>__wsum wsum</code>
</li>
<li>
<b>Param removed. </b>
<code>__wsum sum</code>
</li>
</ul>
</details>
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
