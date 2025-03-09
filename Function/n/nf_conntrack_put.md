# Function: <code>nf_conntrack_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585065267,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3299",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585080588,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3299",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586206787,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3299",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/skbuff.c:skb_scrub_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586548379,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3299",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_local_deliver_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586563538,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3299",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586704177,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3299",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586732752,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3299",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586748121,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3299",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586859872,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3299",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:iptunnel_pull_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586879443,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3299",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586930725,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3299",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586954563,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3299",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586956119,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3299",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586990926,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3299",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587006272,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3299",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587131259,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3299",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587260627,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3299",
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
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585453298,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3506",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585472138,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3506",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586630814,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3506",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586991691,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3506",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_local_deliver_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587009490,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3506",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587151759,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3506",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587180768,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3506",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587200256,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3506",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587333021,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3506",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377221,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3506",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587400946,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3506",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587402362,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3506",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587437598,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3506",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587453179,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3506",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587582850,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3506",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587734124,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3506",
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
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585657368,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3558",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586816286,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3558",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587187051,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3558",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_local_deliver_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587204978,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3558",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587350809,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3558",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587380928,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3558",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587400656,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3558",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587535869,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3558",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587580302,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3558",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587604178,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3558",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587605594,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3558",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587640910,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3558",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587656747,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3558",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587786994,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3558",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587949276,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3558",
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
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585743912,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3616",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586943949,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3616",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587319319,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3616",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_local_deliver_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587337090,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3616",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587483892,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3616",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587515263,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3616",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587536490,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3616",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587681605,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3616",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587726424,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3616",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587751818,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3616",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587752556,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3616",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587793566,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3616",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587806078,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3616",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587944321,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3616",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588100135,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3616",
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
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586178380,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3800",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587443908,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3800",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587839965,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3800",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_local_deliver_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587854658,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3800",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588006063,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3800",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588038079,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3800",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588059758,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3800",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588208213,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3800",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588253016,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3800",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588279795,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3800",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588281086,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3800",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588322347,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3800",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588335203,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3800",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588479753,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3800",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588644680,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3800",
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
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586436878,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3810",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587748196,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3810",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588184669,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3810",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_local_deliver_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588199612,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3810",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588357129,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3810",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588389487,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3810",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588411829,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3810",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588559669,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3810",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588607890,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3810",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588634903,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3810",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588636404,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3810",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588679645,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3810",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588692561,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3810",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588843270,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3810",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589011852,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3810",
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
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586582732,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3895",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587877892,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3895",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588370304,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3895",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588384652,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3895",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588547557,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3895",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588580028,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3895",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588603447,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3895",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588756641,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3895",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588818377,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3895",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588850991,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3895",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588852202,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3895",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588894861,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3895",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588911905,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3895",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589066854,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3895",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589236915,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:3895",
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
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586835792,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:4002",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588183172,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:4002",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588773066,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:4002",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588786360,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:4002",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588958646,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:4002",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588991348,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:4002",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589014982,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:4002",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589189567,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:4002",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589251795,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:4002",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589287889,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:4002",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589291798,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:4002",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589335369,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:4002",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589354077,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:4002",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589520647,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:4002",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589688621,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/skbuff.h:4002",
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
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586985276,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588388512,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588996698,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589009960,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589183158,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589215812,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589239657,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589415137,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589477099,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589512321,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589516185,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589559589,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589578204,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589744762,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589913973,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
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
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587817447,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589249122,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589954810,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589970540,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590154254,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590188312,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590213846,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590402145,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590467894,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590504692,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590510632,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590567161,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590583420,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590762905,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:ipv6_raw_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590949082,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587877201,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589247090,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589995594,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590011084,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590203310,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590237592,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590264614,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590460033,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590526363,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590564599,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590570301,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590627145,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590643836,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590822268,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:ipv6_raw_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591010546,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587756416,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589142114,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
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
      "addr": 18446744071589235384,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_reuse_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589908848,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589925516,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590117428,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590151783,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590179080,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590385854,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590451830,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590489914,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590495935,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590550441,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590568204,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590749359,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:ipv6_raw_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590940772,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588350729,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:32",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589862114,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:32",
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
      "addr": 18446744071589946016,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:32",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_reuse_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590675215,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:32",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590692384,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:32",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590894756,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:32",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590932176,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:32",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590959788,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:32",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591179838,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:32",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591253354,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:32",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591294124,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:32",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591301167,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:32",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591360351,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:32",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591379961,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:32",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591566127,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:32",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:ipv6_raw_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591720316,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:32",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591727014,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:32",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591776628,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:32",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void nf_conntrack_put(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589726433,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591418186,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591770153,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:napi_reuse_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592301964,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592320116,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592513120,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071592573774,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592602606,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592838725,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592918381,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592960525,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592967907,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593034311,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593054478,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593257333,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:ipv6_raw_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593421102,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593428625,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593478320,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
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
      "addr": 18446744071592513120,
      "name": "nf_conntrack_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void nf_conntrack_put(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591349922,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593191034,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593561856,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:napi_reuse_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594138206,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594157060,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594368272,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071594435567,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594466720,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594715863,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594799277,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594846553,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594854275,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594926071,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594947077,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595159141,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:ipv6_raw_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595333440,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595341777,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595400000,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
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
      "addr": 18446744071594368272,
      "name": "nf_conntrack_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void nf_conntrack_put(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591711651,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591759861,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593649451,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594030625,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:napi_reuse_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594525342,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594544478,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594756672,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071594825510,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594857759,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595107853,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595190641,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595237704,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595245444,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595317699,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595339851,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595540867,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595553478,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595617860,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595728527,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595736721,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595795567,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
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
      "addr": 18446744071594756672,
      "name": "nf_conntrack_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void nf_conntrack_put(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592455377,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592505394,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594425330,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594817713,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:napi_reuse_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595328030,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595347070,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595563344,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071595636790,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595668786,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595920524,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596031391,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596078374,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596085940,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596159123,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596180571,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596383617,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596396198,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596443344,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446744071596576351,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/seg6_iptunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596584545,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596646266,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:34",
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
      "addr": 18446744071595563344,
      "name": "nf_conntrack_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071596443344,
      "name": "nf_conntrack_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499982052,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501902740,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502602564,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502617048,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502800700,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502839264,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502867016,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503065588,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503135308,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503176508,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503182352,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503231616,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503253272,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503439196,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503637764,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
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
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232508652,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 3234669444,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 3235307956,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 3235322836,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 3235504316,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3235538504,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235563160,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3235750244,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 3235815264,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3235852388,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 3235857144,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 3235904472,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 3235926192,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 3236097692,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 3236280372,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
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
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293306952,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295313280,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296193940,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296210580,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296441856,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296491324,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296523652,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296769180,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296856104,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296904984,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296910660,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296975956,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296997824,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297221376,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297457348,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
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
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277053762,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278218706,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278753544,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278765454,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278917928,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278948250,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278970158,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279125130,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279181404,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279218832,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279223158,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279265914,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279281134,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279426354,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279586900,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
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
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586742221,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587995296,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588603082,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588616344,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588789542,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588822196,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588846041,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589019567,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589081467,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589116689,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589120553,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589163957,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589182572,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589349130,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589518341,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
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
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586609437,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587708400,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588315066,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328328,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588501478,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588534132,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588557977,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588742623,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588806507,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588841729,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588845593,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588888949,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588907564,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589074122,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589244405,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
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
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586939836,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588327072,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588932368,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/netfilter/nf_conntrack_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_core.c:nf_ct_iterate_cleanup",
        "net/netfilter/nf_conntrack_core.c:nf_conntrack_update",
        "net/netfilter/nf_conntrack_core.c:nf_conntrack_in",
        "net/netfilter/nf_conntrack_core.c:nf_conntrack_in",
        "net/netfilter/nf_conntrack_core.c:gc_worker",
        "net/netfilter/nf_conntrack_core.c:early_drop",
        "net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm",
        "net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm",
        "net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get",
        "net/netfilter/nf_conntrack_core.c:destroy_conntrack"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/netfilter/nf_conntrack_standalone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_standalone.c:ct_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/netfilter/nf_conntrack_expect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_expect.c:nf_ct_find_expectation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588954834,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/netfilter/nf_conntrack_proto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_proto.c:ipv6_getorigdst",
        "net/netfilter/nf_conntrack_proto.c:getorigdst"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/netfilter/nf_conntrack_proto_icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_inet_error"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/netfilter/nf_conntrack_ecache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_ecache.c:ecache_work_evict_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589006337,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/netfilter/nf_conntrack_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_expect",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_new_conntrack",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_new_conntrack",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_list",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_done_list",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_conntrack",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_conntrack",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_conntrack",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_conntrack",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_conntrack",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589039258,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589052520,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589225718,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589258372,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589282217,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589455951,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589518331,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589553553,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589557417,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589600821,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589619436,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589785994,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589959605,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
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
  "name": "nf_conntrack_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587038913,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588462496,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589078298,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589091704,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589265846,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589299428,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589323625,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589502085,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589565367,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589600972,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589604921,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589649093,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589667868,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589836730,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590004151,
      "name": "nf_conntrack_put",
      "external": false,
      "loc": "include/linux/netfilter/nf_conntrack_common.h:31",
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void nf_conntrack_put(struct nf_conntrack * nfct)
```
</details>
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
