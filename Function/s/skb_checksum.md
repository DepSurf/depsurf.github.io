# Function: <code>skb_checksum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586216624,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2176",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment"
      ],
      "caller_func": [
        "net/core/datagram.c:__skb_checksum_complete_head",
        "net/core/datagram.c:__skb_checksum_complete",
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp.c:udp_set_csum",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp_offload.c:skb_udp_tunnel_segment",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/netfilter.c:nf_ip6_checksum_partial",
        "net/ipv6/ip6_checksum.c:udp6_set_csum",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586216624,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586655647,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2174",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment"
      ],
      "caller_func": [
        "net/core/datagram.c:__skb_checksum_complete",
        "net/core/datagram.c:__skb_checksum_complete_head",
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum_partial",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/netfilter.c:nf_ip6_checksum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586635344,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586840400,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2150",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment"
      ],
      "caller_func": [
        "net/core/datagram.c:__skb_checksum_complete",
        "net/core/datagram.c:__skb_checksum_complete_head",
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum_partial",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/netfilter.c:nf_ip6_checksum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586820752,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586965825,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2164",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment"
      ],
      "caller_func": [
        "net/core/datagram.c:__skb_checksum_complete",
        "net/core/datagram.c:__skb_checksum_complete_head",
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum_partial",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/netfilter.c:nf_ip6_checksum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586938288,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587463816,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2532",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment"
      ],
      "caller_func": [
        "net/core/datagram.c:__skb_checksum_complete",
        "net/core/datagram.c:__skb_checksum_complete_head",
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum_partial",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/netfilter.c:nf_ip6_checksum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587431696,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587769175,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2548",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/datagram.c:__skb_checksum_complete",
        "net/core/datagram.c:__skb_checksum_complete_head",
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/netfilter.c:nf_ip6_checksum_partial",
        "net/ipv6/netfilter.c:nf_ip6_checksum",
        "net/ipv6/netfilter.c:nf_ip6_checksum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587736032,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587902914,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2544",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587870176,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588209395,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2710",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588176128,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588414439,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2712",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588381296,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589280259,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2711",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589245920,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589280298,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2728",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884_validate",
        "net/ipv4/gre_offload.c:gre_gso_segment",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589245184,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589174296,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2811",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589139984,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589895181,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2883",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/mptcp/protocol.c:mptcp_update_data_checksum",
        "net/mptcp/subflow.c:validate_data_csum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589859536,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591423892,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2932",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:skb_checksum_help",
        "net/core/gro.c:__skb_gro_checksum_complete",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/mptcp/protocol.c:mptcp_update_data_checksum",
        "net/mptcp/subflow.c:validate_data_csum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591386032,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593187967,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:3138",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:skb_checksum_help",
        "net/core/gro.c:__skb_gro_checksum_complete",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/mptcp/protocol.c:mptcp_update_data_checksum",
        "net/mptcp/subflow.c:validate_data_csum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593147888,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593646604,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:3308",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:skb_checksum_help",
        "net/core/gro.c:__skb_gro_checksum_complete",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/mptcp/protocol.c:mptcp_update_data_checksum",
        "net/mptcp/subflow.c:validate_data_csum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593601632,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594422550,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:3396",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:skb_checksum_help",
        "net/core/gro.c:__skb_gro_checksum_complete",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv4/icmp.c:ip_icmp_error_rfc4884",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/mptcp/protocol.c:mptcp_update_data_checksum",
        "net/mptcp/subflow.c:validate_data_csum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594376224,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501931456,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2712",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501891736,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234690536,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2712",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234655640,
      "name": "skb_checksum",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295351672,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2712",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295305616,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278241112,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2712",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278211814,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588021223,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2712",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587988080,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587734311,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2712",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587701184,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588352999,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2712",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588319856,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
__wsum skb_checksum(const struct sk_buff * skb, int offset, int len, __wsum csum)
```

```json
{
  "name": "skb_checksum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588488519,
      "name": "skb_checksum",
      "external": true,
      "loc": "net/core/skbuff.c:2712",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:__skb_checksum_complete",
        "net/core/skbuff.c:__skb_checksum_complete_head",
        "net/core/skbuff.c:pskb_trim_rcsum_slow"
      ],
      "caller_func": [
        "net/core/dev.c:__skb_gro_checksum_complete",
        "net/core/dev.c:skb_checksum_help",
        "net/netfilter/utils.c:nf_checksum_partial",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/netfilter/utils.c:nf_ip6_checksum",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/udp.c:udp4_hwcsum",
        "net/ipv4/ipmr.c:pim_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588455232,
      "name": "skb_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
