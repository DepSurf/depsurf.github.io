# Function: <code>nf_conntrack_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586517504,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:382",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/virtio_net.c:start_xmit",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pull_header",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586517504,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586959920,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:382",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/virtio_net.c:start_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586959920,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587154752,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:391",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587154752,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587287264,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:320",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587287264,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587808000,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:547",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808000,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588150800,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:594",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588150800,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588333952,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:594",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588333952,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588734144,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:573",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588734144,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588957952,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:573",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588957952,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589912352,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:593",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_encap",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589912352,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589953328,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:670",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_encap",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589953328,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589868160,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:670",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/dev.c:napi_reuse_skb",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589868160,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590628672,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:671",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/dev.c:napi_reuse_skb",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590628672,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592251888,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:699",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/gro.c:napi_reuse_skb",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:nf_conntrack_put",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_encap",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592251888,
      "name": "nf_conntrack_destroy",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594085776,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:696",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/gro.c:napi_reuse_skb",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:nf_conntrack_put",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_encap",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:ipv6_raw_deliver",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594085776,
      "name": "nf_conntrack_destroy",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594470656,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:708",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/virtio_net.c:start_xmit",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/gro.c:napi_reuse_skb",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:nf_conntrack_put",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_encap",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594470656,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595272976,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:714",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/virtio_net.c:start_xmit",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/gro.c:napi_reuse_skb",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:nf_conntrack_put",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_encap",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/tcp_ipv6.c:nf_conntrack_put",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_local.c:end_dt_vrf_core",
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:input_action_end_dx6",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595272976,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502559632,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:573",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502559632,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235266744,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:573",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235266744,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296136848,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:573",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296136848,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278719128,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:573",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/raw.c:raw_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278719128,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588564336,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:573",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588564336,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588276320,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:573",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588276320,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588896512,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:573",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/netfilter/nf_conntrack_core.c:nf_ct_iterate_cleanup",
        "net/netfilter/nf_conntrack_core.c:nf_conntrack_update",
        "net/netfilter/nf_conntrack_core.c:nf_conntrack_in",
        "net/netfilter/nf_conntrack_core.c:nf_conntrack_in",
        "net/netfilter/nf_conntrack_core.c:gc_worker",
        "net/netfilter/nf_conntrack_core.c:early_drop",
        "net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm",
        "net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm",
        "net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get",
        "net/netfilter/nf_conntrack_core.c:destroy_conntrack",
        "net/netfilter/nf_conntrack_standalone.c:ct_seq_show",
        "net/netfilter/nf_conntrack_expect.c:nf_ct_find_expectation",
        "net/netfilter/nf_conntrack_proto.c:ipv6_getorigdst",
        "net/netfilter/nf_conntrack_proto.c:getorigdst",
        "net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_inet_error",
        "net/netfilter/nf_conntrack_ecache.c:ecache_work_evict_list",
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
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_done",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588896512,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void nf_conntrack_destroy(struct nf_conntrack * nfct)
```

```json
{
  "name": "nf_conntrack_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589040224,
      "name": "nf_conntrack_destroy",
      "external": true,
      "loc": "net/netfilter/core.c:573",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589040224,
      "name": "nf_conntrack_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
