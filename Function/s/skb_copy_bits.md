# Function: <code>skb_copy_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580357952,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:795",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_prog_run",
        "kernel/bpf/core.c:__bpf_prog_run",
        "kernel/bpf/core.c:__bpf_prog_run",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/filter.c:bpf_l3_csum_replace",
        "net/core/filter.c:bpf_l4_csum_replace",
        "net/core/filter.c:bpf_skb_store_bytes",
        "net/ethernet/eth.c:eth_type_trans",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586213984,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 737
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580414816,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:1088",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_prog_run",
        "kernel/bpf/core.c:__bpf_prog_run",
        "kernel/bpf/core.c:__bpf_prog_run",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/ethernet/eth.c:eth_type_trans",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586632480,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580463568,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:1171",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_prog_run",
        "kernel/bpf/core.c:__bpf_prog_run",
        "kernel/bpf/core.c:__bpf_prog_run",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/ethernet/eth.c:eth_type_trans",
        "net/ipv4/route.c:ip_route_input_noref",
        "net/ipv4/route.c:ip_route_input_noref",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586817216,
      "name": "skb_copy_bits",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580482864,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:1428",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:___bpf_prog_run",
        "kernel/bpf/core.c:___bpf_prog_run",
        "kernel/bpf/core.c:___bpf_prog_run",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/ethernet/eth.c:eth_type_trans",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586948304,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580542176,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:1674",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/ethernet/eth.c:eth_type_trans",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587440832,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 605
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580626208,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:1844",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/ethernet/eth.c:eth_type_trans",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587745248,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580686560,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2098",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/ethernet/eth.c:eth_type_trans",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587879424,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580753936,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2102",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_flow_dissector_load_bytes",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/ethernet/eth.c:eth_type_trans",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588213155,
      "name": "skb_copy_bits.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071588184576,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580804528,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2102",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_flow_dissector_load_bytes",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/ethernet/eth.c:eth_type_trans",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588389936,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580922544,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2225",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_arp",
        "net/core/flow_dissector.c:__skb_flow_dissect_arp",
        "net/core/flow_dissector.c:skb_flow_get_icmp_tci",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:qdisc_pkt_len_init",
        "net/core/dev.c:qdisc_pkt_len_init",
        "net/core/dev.c:skb_network_protocol",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_ecn_set_ce",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_flow_dissector_load_bytes",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/core/filter.c:INET_ECN_set_ce",
        "net/core/tso.c:tso_start",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/ethernet/eth.c:eth_type_trans",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/xfrm/espintcp.c:espintcp_parse",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589249440,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580918880,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2274",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_arp",
        "net/core/flow_dissector.c:__skb_flow_dissect_arp",
        "net/core/flow_dissector.c:skb_flow_get_icmp_tci",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:qdisc_pkt_len_init",
        "net/core/dev.c:qdisc_pkt_len_init",
        "net/core/dev.c:skb_network_protocol",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_ecn_set_ce",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_flow_dissector_load_bytes",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/core/filter.c:INET_ECN_set_ce",
        "net/core/tso.c:tso_start",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/ethernet/eth.c:eth_type_trans",
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884_validate",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884_validate",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/xfrm/espintcp.c:espintcp_parse",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589248704,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580922784,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2408",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_arp",
        "net/core/flow_dissector.c:__skb_flow_dissect_arp",
        "net/core/flow_dissector.c:skb_flow_get_icmp_tci",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:qdisc_pkt_len_init",
        "net/core/dev.c:qdisc_pkt_len_init",
        "net/core/dev.c:skb_network_protocol",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_ecn_set_ce",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_flow_dissector_load_bytes",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/core/filter.c:INET_ECN_set_ce",
        "net/core/tso.c:tso_start",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/ethernet/eth.c:eth_type_trans",
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884",
        "net/ipv4/icmp.c:icmp_echo",
        "net/ipv4/icmp.c:icmp_echo",
        "net/ipv4/icmp.c:icmp_echo",
        "net/ipv4/icmp.c:icmp_echo",
        "net/ipv4/icmp.c:icmp_echo",
        "net/ipv4/icmp.c:icmp_echo",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/xfrm/espintcp.c:espintcp_parse",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589141072,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581125248,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2428",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_arp",
        "net/core/flow_dissector.c:__skb_flow_dissect_arp",
        "net/core/flow_dissector.c:skb_flow_get_icmp_tci",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:qdisc_pkt_len_init",
        "net/core/dev.c:qdisc_pkt_len_init",
        "net/core/dev.c:skb_network_protocol",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_ecn_set_ce",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_flow_dissector_load_bytes",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/core/filter.c:INET_ECN_set_ce",
        "net/core/tso.c:tso_start",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/ethernet/eth.c:eth_type_trans",
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/xfrm/espintcp.c:espintcp_parse",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589860848,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581395056,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2728",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:bounce_skb",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_arp",
        "net/core/flow_dissector.c:__skb_flow_dissect_arp",
        "net/core/flow_dissector.c:skb_flow_get_icmp_tci",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:qdisc_pkt_len_init",
        "net/core/dev.c:qdisc_pkt_len_init",
        "net/core/dev.c:skb_network_protocol",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_ecn_set_ce",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_flow_dissector_load_bytes",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/core/filter.c:INET_ECN_set_ce",
        "net/core/tso.c:tso_start",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/ethernet/eth.c:eth_type_trans",
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment",
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884",
        "net/ipv4/icmp.c:icmp_timestamp",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/xfrm/espintcp.c:espintcp_parse",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_parse_headers",
        "net/mctp/route.c:mctp_do_fragment_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591388320,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581745088,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2729",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_arp",
        "net/core/flow_dissector.c:__skb_flow_dissect_arp",
        "net/core/flow_dissector.c:skb_flow_get_icmp_tci",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:qdisc_pkt_len_init",
        "net/core/dev.c:qdisc_pkt_len_init",
        "net/core/dev.c:skb_network_protocol",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_ecn_set_ce",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_flow_dissector_load_bytes",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/core/filter.c:INET_ECN_set_ce",
        "net/core/tso.c:tso_start",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/ethernet/eth.c:eth_type_trans",
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment",
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884",
        "net/ipv4/icmp.c:icmp_timestamp",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/xfrm/espintcp.c:espintcp_parse",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_parse_headers",
        "net/mctp/route.c:mctp_do_fragment_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593155840,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581904752,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2751",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_dynptr_slice",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_arp",
        "net/core/flow_dissector.c:__skb_flow_dissect_arp",
        "net/core/flow_dissector.c:skb_flow_get_icmp_tci",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:qdisc_pkt_len_init",
        "net/core/dev.c:qdisc_pkt_len_init",
        "net/core/dev.c:skb_network_protocol",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_ecn_set_ce",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_flow_dissector_load_bytes",
        "net/core/filter.c:__bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/core/filter.c:INET_ECN_set_ce",
        "net/core/tso.c:tso_start",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/ethernet/eth.c:eth_type_trans",
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment",
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884",
        "net/ipv4/icmp.c:icmp_timestamp",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/xfrm/espintcp.c:espintcp_parse",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/seg6_local.c:seg6_pop_srh",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_parse_headers",
        "net/mctp/route.c:mctp_do_fragment_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593610704,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582028944,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2931",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_dynptr_slice",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_gre",
        "net/core/flow_dissector.c:__skb_flow_dissect_arp",
        "net/core/flow_dissector.c:__skb_flow_dissect_arp",
        "net/core/flow_dissector.c:skb_flow_get_icmp_tci",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:skb_network_protocol",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_ecn_set_ce",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_flow_dissector_load_bytes",
        "net/core/filter.c:__bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/core/filter.c:INET_ECN_set_ce",
        "net/core/tso.c:tso_start",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/ethernet/eth.c:eth_type_trans",
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment",
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884",
        "net/ipv4/icmp.c:icmp_timestamp",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/icmp.c:icmp_build_probe",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/xfrm/espintcp.c:espintcp_parse",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_push_pending_frames",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/seg6_local.c:seg6_pop_srh",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_parse_headers",
        "net/mctp/route.c:mctp_do_fragment_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594383872,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492120192,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2102",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_flow_dissector_load_bytes",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/ethernet/eth.c:eth_type_trans",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501898824,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226020968,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2102",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_flow_dissector_load_bytes",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/ethernet/eth.c:eth_type_trans",
        "net/ipv4/route.c:ip_multipath_l3_keys",
        "net/ipv4/route.c:ip_multipath_l3_keys",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234664928,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285328128,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2102",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_flow_dissector_load_bytes",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/ethernet/eth.c:eth_type_trans",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295316224,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 800
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272291558,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2102",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/smack/smack_lsm.c:smk_skb_to_addr_ipv6",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_flow_dissector_load_bytes",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/ethernet/eth.c:eth_type_trans",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278210040,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580773328,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2102",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_flow_dissector_load_bytes",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/ethernet/eth.c:eth_type_trans",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587996720,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580719504,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2102",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_flow_dissector_load_bytes",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/ethernet/eth.c:eth_type_trans",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587709824,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580764576,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2102",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_flow_dissector_load_bytes",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/ethernet/eth.c:eth_type_trans",
        "net/netfilter/nfnetlink_log.c:__build_packet_message",
        "net/netfilter/nf_conntrack_core.c:get_l4proto",
        "net/netfilter/nf_conntrack_core.c:get_l4proto",
        "net/netfilter/nf_conntrack_core.c:nf_ct_get_tuple",
        "net/netfilter/nf_conntrack_core.c:nf_ct_get_tuple",
        "net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet",
        "net/netfilter/nf_conntrack_proto_tcp.c:tcp_in_window",
        "net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udplite_packet",
        "net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet",
        "net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_icmpv4_error",
        "net/netfilter/nf_conntrack_proto_icmp.c:icmp_pkt_to_tuple",
        "net/netfilter/nf_conntrack_proto_icmpv6.c:nf_conntrack_icmpv6_error",
        "net/netfilter/nf_conntrack_proto_icmpv6.c:icmpv6_pkt_to_tuple",
        "net/netfilter/nf_conntrack_proto_dccp.c:nf_conntrack_dccp_packet",
        "net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet",
        "net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet",
        "net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet",
        "net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet",
        "net/netfilter/nf_conntrack_proto_gre.c:gre_pkt_to_tuple",
        "net/netfilter/nf_conntrack_proto_gre.c:gre_pkt_to_tuple",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588328496,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int skb_copy_bits(const struct sk_buff * skb, int offset, void * to, int len)
```

```json
{
  "name": "skb_copy_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580822736,
      "name": "skb_copy_bits",
      "external": true,
      "loc": "kernel/bpf/core.c:2102",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:ipv6_skb_to_auditdata",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:skb_copy",
        "net/core/flow_dissector.c:__skb_get_poff",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/flow_dissector.c:__skb_flow_get_ports",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/filter.c:sk_reuseport_load_bytes",
        "net/core/filter.c:bpf_skb_copy",
        "net/core/filter.c:bpf_flow_dissector_load_bytes",
        "net/core/filter.c:bpf_skb_load_bytes",
        "net/core/filter.c:bpf_skb_load_helper_32_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_32",
        "net/core/filter.c:bpf_skb_load_helper_16_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_16",
        "net/core/filter.c:bpf_skb_load_helper_8_no_cache",
        "net/core/filter.c:bpf_skb_load_helper_8",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/ethernet/eth.c:eth_type_trans",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/route.c:ip6_multipath_l3_keys",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_find_hdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/exthdrs_core.c:ipv6_skip_exthdr",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588463920,
      "name": "skb_copy_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
