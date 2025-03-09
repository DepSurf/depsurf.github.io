# Function: <code>refdst_drop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586206726,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/skbuff.c:skb_scrub_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586267829,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_fill_metadata_dst",
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:__dev_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586335871,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586388903,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586535413,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586553341,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586559016,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586563473,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586586164,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586643780,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586697521,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586720398,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586859977,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586879136,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586890386,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586930786,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586954629,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586956066,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586990865,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587066054,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587119649,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587126426,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587160884,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587182532,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587209542,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587224734,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587260605,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:278",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586630765,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586726127,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586768718,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586827786,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586978198,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586996822,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587002157,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587009425,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587029364,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587098294,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587145680,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587167201,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587327712,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587337674,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377284,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587401014,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587402305,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587437537,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587518422,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587570936,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587582201,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587587423,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587613556,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587636964,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587666348,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587681755,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587734104,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
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
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586816237,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586911999,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586955294,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587016218,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587176257,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_noref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587192150,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587197469,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587204913,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587225306,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587295825,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587343728,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587366385,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587530486,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587540592,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587580365,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587604246,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587605537,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587640849,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587722559,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587775347,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587786345,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587791695,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587818165,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587841924,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587874812,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587890118,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587907212,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587949256,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:275",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
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
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586943917,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587023094,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587080023,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587143429,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587305263,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587324132,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587329734,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587337041,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587357428,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587426404,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587476880,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587498753,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587667199,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587686528,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587726488,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587752046,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587752504,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587793521,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587874977,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587931285,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587943139,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587949102,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587974684,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587998570,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588031092,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588047369,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588064928,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588100112,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:281",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
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
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587443830,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587521126,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587581687,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587648917,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587826919,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587844978,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587850354,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587854609,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587877374,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587949088,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588020849,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588193327,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588213312,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588253091,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588280524,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588281034,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588322305,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588410468,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588466597,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588478707,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588484846,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588510604,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588535162,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588564621,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588585020,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588603872,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588608918,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588644662,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:284",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
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
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587748118,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587814214,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587895372,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587967403,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588170468,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588189327,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588194963,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588199457,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588222654,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588298976,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588371905,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588547223,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588568032,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588607963,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588635088,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588636746,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588679473,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588771214,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588826169,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588842731,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588848135,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588875057,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588899450,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588930004,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588949429,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588969329,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588973098,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589011834,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
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
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587877868,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587949014,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588038540,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588118524,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588354516,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588373828,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588378639,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588384497,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588409886,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588487872,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588541706,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588562289,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588743562,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588765440,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588818428,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588851203,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588852843,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588894689,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588991382,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589048863,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589066313,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589071537,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589098092,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589122932,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589153940,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589173888,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589193406,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589197140,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589236897,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
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
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588183148,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588258503,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588349386,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588437444,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588557499,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588757836,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588774870,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588781847,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588786189,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_mc_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588813678,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588896848,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588952299,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588973409,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589175745,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589198588,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589251566,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589287982,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589292252,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589335203,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589407623,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589502513,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589520069,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589525410,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589553083,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589577761,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589608166,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589626614,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589646900,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589650638,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589688602,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
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
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588388492,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588463623,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588555831,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588643860,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588774461,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/core/lwt_bpf.c:bpf_input",
        "net/core/lwt_bpf.c:bpf_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588981612,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588998470,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589005431,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589009789,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_mc_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589036974,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589120976,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589176813,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589197825,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589400750,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589423916,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589476870,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589512406,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589516627,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589559425,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589631863,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589726545,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589744181,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589749490,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589777115,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589802145,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589832550,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589850790,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589871108,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589874949,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589913954,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
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
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589249197,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589334660,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589408607,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589502156,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589646064,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/core/lwt_bpf.c:bpf_input",
        "net/core/lwt_bpf.c:bpf_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589940884,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589957979,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589963762,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589970740,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_mc_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589997844,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590088769,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590148630,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590170137,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590390232,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590411212,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590468182,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590505769,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590506336,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:skb_dst_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590567267,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590642226,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590746383,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590762377,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590768236,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590796900,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590827591,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590863247,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590878266,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590898699,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590904051,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590949642,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void refdst_drop(long unsigned int refdst)
```

```json
{
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589247165,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589335700,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589409477,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589504556,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589669815,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/core/lwt_bpf.c:bpf_input",
        "net/core/lwt_bpf.c:bpf_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589787578,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/sched/sch_frag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589981844,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589998795,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590004564,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590011284,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_mc_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590039588,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590134884,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590196291,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590219289,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590448558,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590469552,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590526681,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590559808,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    },
    {
      "addr": 18446744071590565904,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:skb_dst_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590627251,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590702106,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590805359,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590821753,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590827505,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590856152,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590887671,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590924061,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590939528,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590960165,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590964195,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591011034,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:255",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590559808,
      "name": "refdst_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void refdst_drop(long unsigned int refdst)
```

```json
{
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589142189,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589266732,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589308515,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589402565,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589561292,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/core/lwt_bpf.c:bpf_input",
        "net/core/lwt_bpf.c:bpf_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589652158,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589691566,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/sched/sch_frag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589895692,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589912795,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589918793,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589925716,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_mc_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589954166,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590049343,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590110419,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590133384,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590374081,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590395430,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590451947,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590485152,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    },
    {
      "addr": 18446744071590495620,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590550547,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590627914,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590732210,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590748826,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590754701,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590785079,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590816731,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590853585,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590869109,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590890231,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590894803,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590941235,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590485152,
      "name": "refdst_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
void refdst_drop(long unsigned int refdst)
```

```json
{
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589862189,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589992790,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590041520,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590128843,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590306357,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590409210,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590449296,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/sched/sch_frag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590661276,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590679243,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590685365,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590692621,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_mc_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590721274,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590822750,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590887412,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590913314,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591166726,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591190783,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591253525,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591288752,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    },
    {
      "addr": 18446744071591300830,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591360487,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591441302,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591544879,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591565589,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591571613,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591602919,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591635515,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591682529,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591699311,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591722080,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output_core",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591727216,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx4_finish",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591777099,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:258",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591288752,
      "name": "refdst_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
void refdst_drop(long unsigned int refdst)
```

```json
{
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591418352,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591533544,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591570483,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591680445,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591891124,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592001216,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592050780,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/sched/sch_frag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592286658,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592307703,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592311023,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592320347,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_mc_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592350012,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592460642,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592525613,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592553030,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592823761,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592850428,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592918588,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592954816,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    },
    {
      "addr": 18446744071592967660,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593034508,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593120613,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593234648,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593256912,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593262888,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593296325,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593329182,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593379926,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593397809,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593423041,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output_core",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593428886,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx4_finish",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593444283,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/ipv6/ioam6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6_iptunnel.c:ioam6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593478874,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:259",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592954816,
      "name": "refdst_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void refdst_drop(long unsigned int refdst)
```

```json
{
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593191200,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593306560,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:tun_dst_unclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593361977,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593475741,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593693492,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593821161,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593869324,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/sched/sch_frag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594123010,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594144201,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594147691,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594157291,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_mc_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594186060,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594314978,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594380879,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594412166,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594700326,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594727564,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594799484,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594840640,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    },
    {
      "addr": 18446744071594854009,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594926268,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595016853,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595135206,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595158711,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595165320,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595200348,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595234734,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595284736,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595307633,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595335505,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output_core",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595342053,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx4_finish",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595360267,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/ipv6/ioam6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6_iptunnel.c:ioam6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595400554,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:253",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594840640,
      "name": "refdst_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void refdst_drop(long unsigned int refdst)
```

```json
{
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593649655,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593768652,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:tun_dst_unclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593825622,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593941645,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594174331,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594195887,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594244236,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/sched/sch_frag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594509960,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594531328,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594534854,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594544709,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_mc_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594573134,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594701394,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594771886,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594801558,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595092262,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595119644,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595191014,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595231952,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    },
    {
      "addr": 18446744071595245143,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595317898,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595410335,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595525292,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595554229,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595560680,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595596081,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595628593,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595679920,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595702625,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595730564,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output_core",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595736985,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx4_finish",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595757449,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/ipv6/ioam6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6_iptunnel.c:ioam6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595796131,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:267",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595231952,
      "name": "refdst_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void refdst_drop(long unsigned int refdst)
```

```json
{
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594425457,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594548104,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:tun_dst_unclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594607174,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594724413,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594970862,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute",
        "net/core/lwt_bpf.c:bpf_lwt_input_reroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594992815,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595041542,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/sched/sch_frag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment",
        "net/sched/sch_frag.c:sch_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595313112,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595334064,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595337558,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595347301,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_mc_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595376402,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595505933,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595582645,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595612784,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595904971,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595932402,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596031699,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596072496,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    },
    {
      "addr": 18446744071596085636,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596159322,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596252034,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596371970,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596396946,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596403400,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596438945,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596526653,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596550850,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596578369,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output_core",
        "net/ipv6/seg6_iptunnel.c:seg6_input_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596584805,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx4_finish",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596605622,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/ipv6/ioam6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6_iptunnel.c:ioam6_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596646798,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:260",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596072496,
      "name": "refdst_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501902724,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501987856,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502096408,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502218992,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502340256,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/core/lwt_bpf.c:bpf_input",
        "net/core/lwt_bpf.c:bpf_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502587128,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502606084,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502611548,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502616900,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_mc_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502646604,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502736960,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502794700,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502817696,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503053692,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503076724,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503135364,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503176728,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503181828,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503231468,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503336608,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503420240,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503438576,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503444100,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503481888,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503507944,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503542324,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503568236,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503589728,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503594412,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503637756,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
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
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234669384,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 3234745104,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 3234839616,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 3234941684,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3235080948,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/core/lwt_bpf.c:bpf_input",
        "net/core/lwt_bpf.c:bpf_input"
      ],
      "caller_func": []
    },
    {
      "addr": 3235292136,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 3235309940,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3235317820,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 3235322664,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_mc_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 3235350920,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3235440836,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3235497708,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 3235519376,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235738616,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 3235759760,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 3235815332,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3235852640,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 3235856672,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 3235904304,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 3235982484,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 3236076056,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3236097040,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3236102420,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 3236132600,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3236161016,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3236194196,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2"
      ],
      "caller_func": []
    },
    {
      "addr": 3236214452,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 3236235440,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input"
      ],
      "caller_func": []
    },
    {
      "addr": 3236239632,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 3236280356,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
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
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295313252,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295422860,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295552944,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295667336,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295863880,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/core/lwt_bpf.c:bpf_input",
        "net/core/lwt_bpf.c:bpf_input"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296175196,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296196304,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296205456,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296210424,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_mc_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296246856,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296360536,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296430536,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296464340,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296748084,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296781712,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296855840,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296905104,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296910104,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296975808,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297072812,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297196448,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297220556,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297227508,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297267356,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297299536,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297345244,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297368124,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297397584,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297403952,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297457332,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
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
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278218686,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278286860,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278369378,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278459198,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278562484,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/core/lwt_bpf.c:bpf_input",
        "net/core/lwt_bpf.c:bpf_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278741678,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278755174,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278761558,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278765316,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_mc_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278787508,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278862452,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278912784,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278931696,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279113232,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279132812,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279181564,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279218996,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279222788,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279265786,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279330454,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279407570,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279425832,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279430490,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279456178,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279479934,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279511390,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279524928,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279544424,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279548104,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279586884,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
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
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587995276,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588070407,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588162567,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588250596,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588380845,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/core/lwt_bpf.c:bpf_input",
        "net/core/lwt_bpf.c:bpf_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588587996,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588604854,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588611815,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588616173,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_mc_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588643358,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588727360,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588783197,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588804209,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589005886,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589028284,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589081238,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589116774,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589120995,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589163793,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589236231,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589330913,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589348549,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589353858,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589381483,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589406513,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589436918,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589455158,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589475476,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589479317,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589518322,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
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
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587708380,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587783831,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587875399,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587963412,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588093533,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/core/lwt_bpf.c:bpf_input",
        "net/core/lwt_bpf.c:bpf_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588299980,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588316838,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588323799,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328157,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_mc_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588355342,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588439344,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588495133,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588516145,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588728942,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588753324,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588806278,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588841814,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588846035,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588888785,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588961223,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589055905,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589073541,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589078850,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589106475,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589131505,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589161910,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589180150,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589200468,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589204309,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589244386,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
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
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588327052,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402183,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588494391,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588582420,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588713021,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/core/lwt_bpf.c:bpf_input",
        "net/core/lwt_bpf.c:bpf_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589024172,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589041030,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589047991,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589052349,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_mc_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589079534,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589163536,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589219373,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589240385,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589442270,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589464668,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589518102,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589553638,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589557859,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589600657,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589673095,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589767777,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589785413,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589790722,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589818347,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589843377,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589873782,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589892022,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589912340,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589916181,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589923700,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/netfilter/nf_conntrack_reasm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue",
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589959586,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
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
  "name": "refdst_drop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588462476,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588538663,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588626487,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:pneigh_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588719908,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588853277,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/core/lwt_bpf.c:bpf_input",
        "net/core/lwt_bpf.c:bpf_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589062895,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589080182,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589087170,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr",
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589091533,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_mc_finish_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589118958,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589203504,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589257101,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589280881,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589487038,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589511036,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv4/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589565138,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589601061,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589605384,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589648929,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589722231,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589818481,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589836149,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589841442,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589869067,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589894657,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589925318,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589944342,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589964888,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_output",
        "net/ipv6/seg6_iptunnel.c:seg6_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589968866,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590004133,
      "name": "refdst_drop",
      "external": false,
      "loc": "include/net/dst.h:256",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void refdst_drop(long unsigned int refdst)
```
</details>
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
