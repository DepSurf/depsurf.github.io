# Function: <code>icmpv6_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmpv6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587234848,
      "name": "icmpv6_send",
      "external": true,
      "loc": "net/ipv6/ip6_icmp.c:33",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_expire_frag_queue",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587234848,
      "name": "icmpv6_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmpv6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587699504,
      "name": "icmpv6_send",
      "external": true,
      "loc": "net/ipv6/ip6_icmp.c:33",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_expire_frag_queue",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587699504,
      "name": "icmpv6_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmpv6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587913872,
      "name": "icmpv6_send",
      "external": true,
      "loc": "net/ipv6/ip6_icmp.c:33",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_expire_frag_queue",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587913872,
      "name": "icmpv6_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmpv6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588072176,
      "name": "icmpv6_send",
      "external": true,
      "loc": "net/ipv6/ip6_icmp.c:33",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_expire_frag_queue",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588072176,
      "name": "icmpv6_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmpv6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588616400,
      "name": "icmpv6_send",
      "external": true,
      "loc": "net/ipv6/ip6_icmp.c:34",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_expire_frag_queue",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588616400,
      "name": "icmpv6_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmpv6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588982352,
      "name": "icmpv6_send",
      "external": true,
      "loc": "net/ipv6/ip6_icmp.c:34",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_expire_frag_queue",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588982352,
      "name": "icmpv6_send",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmpv6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589206384,
      "name": "icmpv6_send",
      "external": true,
      "loc": "net/ipv6/ip6_icmp.c:34",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589206384,
      "name": "icmpv6_send",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmpv6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589660480,
      "name": "icmpv6_send",
      "external": true,
      "loc": "net/ipv6/ip6_icmp.c:34",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589660480,
      "name": "icmpv6_send",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmpv6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589884768,
      "name": "icmpv6_send",
      "external": true,
      "loc": "net/ipv6/ip6_icmp.c:34",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589884768,
      "name": "icmpv6_send",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmpv6_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590913895,
      "name": "icmpv6_send",
      "external": true,
      "loc": "net/ipv6/ip6_icmp.c:34",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send"
      ],
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
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590913552,
      "name": "icmpv6_send",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmpv6_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584033210,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590566381,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590636507,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590644682,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590701990,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590811754,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590856999,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590888244,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590937474,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/xfrm6_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap"
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
  "name": "icmpv6_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584061709,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590492852,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590558083,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590569058,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590627798,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590738747,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590786119,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590817313,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590867122,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/xfrm6_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap"
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
  "name": "icmpv6_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584433389,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591297765,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591369315,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591380842,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591441173,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591555397,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591603974,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591636097,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591697234,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/xfrm6_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmpv6_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585071730,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592964752,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593043093,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593055490,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593120416,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593245133,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593297821,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593329774,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593395186,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/xfrm6_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmpv6_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585793570,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594851088,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594935333,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594948014,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595016656,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595145938,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595201861,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595235326,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595304834,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/xfrm6_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmpv6_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586025342,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595242220,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595327398,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595340655,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595410133,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595541005,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595597589,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595630704,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595699858,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/xfrm6_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmpv6_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586273701,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596083570,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596168635,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596181375,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596251832,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596383747,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596440453,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596478064,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596548082,
      "name": "icmpv6_send",
      "external": false,
      "loc": "include/linux/icmpv6.h:47",
      "file": "net/ipv6/xfrm6_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmpv6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503605944,
      "name": "icmpv6_send",
      "external": true,
      "loc": "net/ipv6/ip6_icmp.c:34",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503605944,
      "name": "icmpv6_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmpv6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236250488,
      "name": "icmpv6_send",
      "external": true,
      "loc": "net/ipv6/ip6_icmp.c:34",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236250488,
      "name": "icmpv6_send",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmpv6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297418256,
      "name": "icmpv6_send",
      "external": true,
      "loc": "net/ipv6/ip6_icmp.c:34",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297418256,
      "name": "icmpv6_send",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmpv6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279558026,
      "name": "icmpv6_send",
      "external": true,
      "loc": "net/ipv6/ip6_icmp.c:34",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279558026,
      "name": "icmpv6_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmpv6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589489136,
      "name": "icmpv6_send",
      "external": true,
      "loc": "net/ipv6/ip6_icmp.c:34",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589489136,
      "name": "icmpv6_send",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmpv6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589214128,
      "name": "icmpv6_send",
      "external": true,
      "loc": "net/ipv6/ip6_icmp.c:34",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "net/ipv4/ip_tunnel.c:tnl_update_pmtu",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589214128,
      "name": "icmpv6_send",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmpv6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589930400,
      "name": "icmpv6_send",
      "external": true,
      "loc": "net/ipv6/ip6_icmp.c:34",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output",
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_expire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589930400,
      "name": "icmpv6_send",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```

```json
{
  "name": "icmpv6_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589979792,
      "name": "icmpv6_send",
      "external": true,
      "loc": "net/ipv6/ip6_icmp.c:34",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589979792,
      "name": "icmpv6_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void icmpv6_send(struct sk_buff * skb, u8 type, u8 code, __u32 info)
```
</details>
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
