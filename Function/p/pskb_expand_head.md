# Function: <code>pskb_expand_head</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586220240,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1190",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_n_string",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_pad",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_segment",
        "net/core/dev.c:skb_checksum_help",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586220240,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 581
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586644608,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1195",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_pad",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586644608,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586829296,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1195",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_pad",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586829296,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586952832,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1197",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586952832,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587448512,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1441",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:do_xdp_generic",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587448512,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587751328,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1443",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:bpf_skb_grow_rcsum",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587751328,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 743
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587886944,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1453",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587886944,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588192160,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1612",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588192160,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588397344,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1612",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:bpf_skb_grow_rcsum",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588397344,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589265168,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1611",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_napi_alloc_frags",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_reorder_vlan_header",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:validate_xmit_vlan",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:bpf_skb_grow_rcsum",
        "net/core/filter.c:bpf_skb_net_shrink",
        "net/core/filter.c:bpf_skb_net_grow",
        "net/core/filter.c:bpf_skb_proto_6_to_4",
        "net/core/filter.c:bpf_skb_proto_4_to_6",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_input.c:ip_rcv_options",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589265168,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589264320,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1622",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_napi_alloc_frags",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_reorder_vlan_header",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:validate_xmit_vlan",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:bpf_skb_grow_rcsum",
        "net/core/filter.c:sk_skb_adjust_room",
        "net/core/filter.c:bpf_skb_net_shrink",
        "net/core/filter.c:bpf_skb_net_grow",
        "net/core/filter.c:bpf_skb_proto_6_to_4",
        "net/core/filter.c:bpf_skb_proto_4_to_6",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_input.c:ip_rcv_options",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589264320,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589148704,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1664",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_napi_alloc_frags",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_reorder_vlan_header",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:validate_xmit_vlan",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:sk_skb_adjust_room",
        "net/core/filter.c:bpf_skb_net_grow",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_input.c:ip_rcv_options",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589148704,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 851
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589868944,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1685",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_napi_alloc_frags",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_reorder_vlan_header",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_expand_head",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:validate_xmit_vlan",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:sk_skb_adjust_room",
        "net/core/filter.c:bpf_skb_net_grow",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_input.c:ip_rcv_options",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output_core",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ioam6_iptunnel.c:ioam6_output",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589868944,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 819
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591398544,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1679",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_napi_alloc_frags",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_reorder_vlan_header",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_expand_head",
        "net/core/skbuff.c:__skb_unclone_keeptruesize",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:sk_skb_adjust_room",
        "net/core/filter.c:bpf_skb_net_grow",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_input.c:ip_rcv_options",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap",
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output_core",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ioam6_iptunnel.c:ioam6_output",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_encap",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/ipv6/ip6_offload.c:ipv6_gso_segment",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591398544,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 854
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593163680,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1878",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_napi_alloc_frags",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_reorder_vlan_header",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_expand_head",
        "net/core/skbuff.c:__skb_unclone_keeptruesize",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:sk_skb_adjust_room",
        "net/core/filter.c:bpf_skb_net_grow",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_input.c:ip_rcv_options",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_input.c:xfrm_prepare_input",
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output_core",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ioam6_iptunnel.c:ioam6_output",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_encap",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593163680,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 875
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593616944,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:2030",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_napi_alloc_frags",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_reorder_vlan_header",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_expand_head",
        "net/core/skbuff.c:__skb_unclone_keeptruesize",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:sk_skb_adjust_room",
        "net/core/filter.c:bpf_skb_net_grow",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/gso.c:__skb_gso_segment",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_input.c:ip_rcv_options",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_input.c:xfrm_prepare_input",
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output_core",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ioam6_iptunnel.c:ioam6_output",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_encap",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593616944,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 963
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594392144,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:2118",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_napi_alloc_frags",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_ensure_writable_head_tail",
        "net/core/skbuff.c:skb_reorder_vlan_header",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_expand_head",
        "net/core/skbuff.c:__skb_unclone_keeptruesize",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:sk_skb_adjust_room",
        "net/core/filter.c:bpf_skb_net_grow",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/gso.c:__skb_gso_segment",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/sched/sch_frag.c:sch_frag_xmit",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_input.c:ip_rcv_options",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:__xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_input.c:xfrm_prepare_input",
        "net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap",
        "net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/xfrm6_input.c:__xfrm6_udp_encap_rcv",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output_core",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/ioam6_iptunnel.c:ioam6_output",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_encap",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594392144,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501913304,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1612",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501913304,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234674040,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1612",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234674040,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295327920,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1612",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295327920,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278225968,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1612",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278225968,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588004128,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1612",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:bpf_skb_grow_rcsum",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588004128,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587717216,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1612",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/vxlan.c:vxlan_build_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:bpf_skb_grow_rcsum",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel.c:ip_tunnel_xmit",
        "net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587717216,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588335904,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1612",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:bpf_skb_grow_rcsum",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588335904,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
int pskb_expand_head(struct sk_buff * skb, int nhead, int ntail, gfp_t gfp_mask)
```

```json
{
  "name": "pskb_expand_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588471376,
      "name": "pskb_expand_head",
      "external": true,
      "loc": "net/core/skbuff.c:1612",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/skbuff.c:skb_mpls_push",
        "net/core/skbuff.c:skb_vlan_push",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__skb_pad",
        "net/core/skbuff.c:skb_realloc_headroom",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__skb_gso_segment",
        "net/core/dev.c:skb_checksum_help",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:sk_skb_change_head",
        "net/core/filter.c:bpf_skb_change_head",
        "net/core/filter.c:bpf_skb_grow_rcsum",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_adjust_room",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/filter.c:bpf_skb_change_proto",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/core/lwt_bpf.c:bpf_lwt_push_ip_encap",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr",
        "net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr",
        "net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588471376,
      "name": "pskb_expand_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
