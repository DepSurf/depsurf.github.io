# Function: <code>___pskb_trim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586220832,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1491",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_segment",
        "net/core/filter.c:sk_filter",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586220832,
      "name": "___pskb_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586645200,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1496",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586645200,
      "name": "___pskb_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586829888,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1496",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586829888,
      "name": "___pskb_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586964080,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1509",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586964080,
      "name": "___pskb_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 801
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
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587461504,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1754",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_checksum_trimmed",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587461504,
      "name": "___pskb_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 866
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
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587765840,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1756",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587765840,
      "name": "___pskb_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 894
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
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587899728,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1766",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587899728,
      "name": "___pskb_trim",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588205984,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1925",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588205984,
      "name": "___pskb_trim",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588411040,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1925",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588411040,
      "name": "___pskb_trim",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589276704,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1924",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589276704,
      "name": "___pskb_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
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
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589276672,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1935",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589276672,
      "name": "___pskb_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 839
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
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589170752,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1977",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589170752,
      "name": "___pskb_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 839
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
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589891552,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:2049",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589891552,
      "name": "___pskb_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 879
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
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591420224,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:2098",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591420224,
      "name": "___pskb_trim",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593183968,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:2301",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593183968,
      "name": "___pskb_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1011
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
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593642256,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:2465",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593642256,
      "name": "___pskb_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1218
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
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594418192,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:2553",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594418192,
      "name": "___pskb_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1215
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
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501928128,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1925",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501928128,
      "name": "___pskb_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 864
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
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234687332,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1925",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv6/ip6_output.c:__ip6_append_data",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234687332,
      "name": "___pskb_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295347248,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1925",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295347248,
      "name": "___pskb_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1144
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
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278238338,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1925",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278238338,
      "name": "___pskb_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
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
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588017824,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1925",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588017824,
      "name": "___pskb_trim",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587730912,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1925",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587730912,
      "name": "___pskb_trim",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588349600,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1925",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588349600,
      "name": "___pskb_trim",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int ___pskb_trim(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "___pskb_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588485120,
      "name": "___pskb_trim",
      "external": true,
      "loc": "net/core/skbuff.c:1925",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_extract",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:pskb_trim_rcsum_slow",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588485120,
      "name": "___pskb_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 854
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
