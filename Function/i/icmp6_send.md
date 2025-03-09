# Function: <code>icmp6_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587133184,
      "name": "icmp6_send",
      "external": false,
      "loc": "net/ipv6/icmp.c:391",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_param_prob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587133184,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2230
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587584768,
      "name": "icmp6_send",
      "external": false,
      "loc": "net/ipv6/icmp.c:391",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587584768,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2525
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587788992,
      "name": "icmp6_send",
      "external": false,
      "loc": "net/ipv6/icmp.c:392",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587788992,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2568
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587946160,
      "name": "icmp6_send",
      "external": false,
      "loc": "net/ipv6/icmp.c:405",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587946160,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2791
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588481840,
      "name": "icmp6_send",
      "external": false,
      "loc": "net/ipv6/icmp.c:420",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588481840,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2861
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588845408,
      "name": "icmp6_send",
      "external": false,
      "loc": "net/ipv6/icmp.c:421",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588845408,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2579
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589068944,
      "name": "icmp6_send",
      "external": false,
      "loc": "net/ipv6/icmp.c:423",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589068944,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2454
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589523152,
      "name": "icmp6_send",
      "external": false,
      "loc": "net/ipv6/icmp.c:423",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589523152,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2128
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589747232,
      "name": "icmp6_send",
      "external": false,
      "loc": "net/ipv6/icmp.c:423",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589747232,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2128
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590765424,
      "name": "icmp6_send",
      "external": false,
      "loc": "net/ipv6/icmp.c:442",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590765424,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2319
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr, const struct inet6_skb_parm * parm)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590824768,
      "name": "icmp6_send",
      "external": true,
      "loc": "net/ipv6/icmp.c:447",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590824768,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2232
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr, const struct inet6_skb_parm * parm)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590751904,
      "name": "icmp6_send",
      "external": true,
      "loc": "net/ipv6/icmp.c:447",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590751904,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2282
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr, const struct inet6_skb_parm * parm)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "icmp6_send",
      "external": true,
      "loc": "net/ipv6/icmp.c:448",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592741188,
      "name": "icmp6_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071591568816,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr, const struct inet6_skb_parm * parm)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "icmp6_send",
      "external": true,
      "loc": "net/ipv6/icmp.c:440",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob_reason",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594627885,
      "name": "icmp6_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593259776,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2553
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr, const struct inet6_skb_parm * parm)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "icmp6_send",
      "external": true,
      "loc": "net/ipv6/icmp.c:440",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob_reason",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596361631,
      "name": "icmp6_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071595162192,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2552
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr, const struct inet6_skb_parm * parm)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "icmp6_send",
      "external": true,
      "loc": "net/ipv6/icmp.c:445",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob_reason",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596890146,
      "name": "icmp6_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071595557504,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2593
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr, const struct inet6_skb_parm * parm)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "icmp6_send",
      "external": true,
      "loc": "net/ipv6/icmp.c:445",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob_reason",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597814525,
      "name": "icmp6_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071596400208,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2622
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503442160,
      "name": "icmp6_send",
      "external": false,
      "loc": "net/ipv6/icmp.c:423",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503442160,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1804
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236100444,
      "name": "icmp6_send",
      "external": false,
      "loc": "net/ipv6/icmp.c:423",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236100444,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1836
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297224976,
      "name": "icmp6_send",
      "external": false,
      "loc": "net/ipv6/icmp.c:423",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297224976,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2340
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279428634,
      "name": "icmp6_send",
      "external": false,
      "loc": "net/ipv6/icmp.c:423",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279428634,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1752
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589351600,
      "name": "icmp6_send",
      "external": false,
      "loc": "net/ipv6/icmp.c:423",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589351600,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2128
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589076592,
      "name": "icmp6_send",
      "external": false,
      "loc": "net/ipv6/icmp.c:423",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589076592,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2128
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589788464,
      "name": "icmp6_send",
      "external": false,
      "loc": "net/ipv6/icmp.c:423",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589788464,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2128
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
void icmp6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info, const struct in6_addr * force_saddr)
```

```json
{
  "name": "icmp6_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589839200,
      "name": "icmp6_send",
      "external": false,
      "loc": "net/ipv6/icmp.c:423",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/icmp.c:icmpv6_param_prob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589839200,
      "name": "icmp6_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2107
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct in6_addr * force_saddr</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct inet6_skb_parm * parm</code>
</li>
</ul>
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
