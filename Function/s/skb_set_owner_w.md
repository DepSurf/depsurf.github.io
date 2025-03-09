# Function: <code>skb_set_owner_w</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586194672,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:1657",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_wmalloc",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586194672,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586617120,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:1673",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586617120,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586801216,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:1671",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586801216,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586925072,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:1814",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586925072,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587417152,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:1825",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:smap_read_sock_strparser",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587417152,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587719728,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:1845",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:smap_read_sock_strparser",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587719728,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587852800,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:1841",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587852800,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588157008,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:1973",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588157008,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588362304,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:1986",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588362304,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589224192,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:2083",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_build_skb",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skmsg.c:sk_psock_skb_redirect",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/xfrm/espintcp.c:espintcp_push_skb",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589224192,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589221072,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:2075",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_build_skb",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/xfrm/espintcp.c:espintcp_push_skb",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ndisc.c:ndisc_alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589221072,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589114624,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:2104",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_build_skb",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/xfrm/espintcp.c:espintcp_push_skb",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ndisc.c:ndisc_alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589114624,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:2228",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_build_skb",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_expand_head",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/xfrm/espintcp.c:espintcp_push_skb",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592692558,
      "name": "skb_set_owner_w.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071589833072,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591356687,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:2395",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_build_skb",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_expand_head",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/xfrm/espintcp.c:espintcp_push_skb",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_alloc_skb",
        "net/mctp/route.c:mctp_do_fragment_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594578021,
      "name": "skb_set_owner_w.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071591356496,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593111359,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:2474",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_build_skb",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_expand_head",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/xfrm/espintcp.c:espintcp_push_skb",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_alloc_skb",
        "net/mctp/route.c:mctp_do_fragment_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596321686,
      "name": "skb_set_owner_w.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593111168,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593566532,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:2523",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_build_skb",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_expand_head",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/xfrm/espintcp.c:espintcp_push_skb",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_alloc_skb",
        "net/mctp/route.c:mctp_do_fragment_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596851384,
      "name": "skb_set_owner_w.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593566352,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594339124,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:2503",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_build_skb",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skbuff.c:skb_expand_head",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/xfrm/espintcp.c:espintcp_push_skb",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_alloc_skb",
        "net/mctp/route.c:mctp_do_fragment_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597776199,
      "name": "skb_set_owner_w.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071594338944,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501865072,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:1986",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501865072,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234635044,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:1986",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_build_skb",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234635044,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295277616,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:1986",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295277616,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278195184,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:1986",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278195184,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587969088,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:1986",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587969088,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587682192,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:1986",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587682192,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588300864,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:1986",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588300864,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void skb_set_owner_w(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_w",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588436192,
      "name": "skb_set_owner_w",
      "external": true,
      "loc": "net/core/sock.c:1986",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wmalloc",
        "net/core/skbuff.c:skb_cow_data",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588436192,
      "name": "skb_set_owner_w",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
