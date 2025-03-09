# Function: <code>skb_scrub_packet</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586210512,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:4286",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586210512,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586630704,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:4327",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586630704,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586816176,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:4371",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586816176,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586943856,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:4465",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586943856,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587439088,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:4858",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587439088,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587744144,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:4897",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587744144,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587877824,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:4919",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587877824,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588183104,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:5104",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588183104,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588388448,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:5116",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588388448,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589249072,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:5218",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589249072,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589247040,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:5285",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_bridge_input",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589247040,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589142064,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:5373",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589142064,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589862064,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:5448",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589862064,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591387808,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:5369",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591387808,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593151376,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:5571",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593151376,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593605120,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:5769",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593605120,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594379312,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:5897",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/netkit.c:netkit_xmit",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594379312,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501902672,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:5116",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501902672,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234663628,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:5116",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234663628,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295313184,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:5116",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295313184,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278218642,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:5116",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278218642,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587995232,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:5116",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587995232,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587708336,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:5116",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/vxlan.c:vxlan_xmit_one",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv4/ip_tunnel.c:ip_tunnel_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587708336,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588327008,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:5116",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588327008,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void skb_scrub_packet(struct sk_buff * skb, bool xnet)
```

```json
{
  "name": "skb_scrub_packet",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588462432,
      "name": "skb_scrub_packet",
      "external": true,
      "loc": "net/core/skbuff.c:5116",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect",
        "net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header",
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588462432,
      "name": "skb_scrub_packet",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
