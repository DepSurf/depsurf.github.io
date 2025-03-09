# Function: <code>__sk_mem_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586195952,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2067",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586195952,
      "name": "__sk_mem_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1172
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
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586610880,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2125",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586610880,
      "name": "__sk_mem_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 835
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
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586796032,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2205",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:sk_stream_alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586796032,
      "name": "__sk_mem_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586920720,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2364",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:sk_stream_alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586920720,
      "name": "__sk_mem_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587413312,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2404",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:sk_stream_alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587413312,
      "name": "__sk_mem_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587715200,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2485",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:smap_tx_work",
        "kernel/bpf/sockmap.c:bpf_exec_tx_verdict",
        "net/core/sock.c:sk_alloc_sg",
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:sk_stream_alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587715200,
      "name": "__sk_mem_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587848640,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2429",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587848640,
      "name": "__sk_mem_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588153024,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2572",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588153024,
      "name": "__sk_mem_schedule",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588358288,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2587",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588358288,
      "name": "__sk_mem_schedule",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589223933,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2695",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_skb_ingress",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/xfrm/espintcp.c:handle_nonesp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589218016,
      "name": "__sk_mem_schedule",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589222609,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2687",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_build_frag",
        "net/ipv4/tcp.c:tcp_build_frag",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/xfrm/espintcp.c:handle_nonesp",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:__mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:__mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:__mptcp_wmem_reserve",
        "net/mptcp/protocol.c:__mptcp_wmem_reserve",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:__mptcp_move_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589216080,
      "name": "__sk_mem_schedule",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589116385,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2710",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_build_frag",
        "net/ipv4/tcp.c:tcp_build_frag",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/xfrm/espintcp.c:handle_nonesp",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:__mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:__mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:__mptcp_move_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589109712,
      "name": "__sk_mem_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589834913,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2841",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_build_frag",
        "net/ipv4/tcp.c:tcp_build_frag",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:__mptcp_move_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589827856,
      "name": "__sk_mem_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591356090,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:3004",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_downgrade_zcopy_pure",
        "net/ipv4/tcp.c:tcp_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/xfrm/espintcp.c:handle_nonesp",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591352720,
      "name": "__sk_mem_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593124218,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:3085",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_downgrade_zcopy_pure",
        "net/ipv4/tcp.c:tcp_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/xfrm/espintcp.c:handle_nonesp",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593123792,
      "name": "__sk_mem_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593576947,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:3146",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_downgrade_zcopy_pure",
        "net/ipv4/tcp.c:tcp_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_output.c:tcp_clone_payload",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/xfrm/espintcp.c:handle_nonesp",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593576512,
      "name": "__sk_mem_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594349419,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:3156",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_downgrade_zcopy_pure",
        "net/ipv4/tcp.c:tcp_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_output.c:tcp_clone_payload",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/xfrm/espintcp.c:handle_nonesp",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594348960,
      "name": "__sk_mem_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501874400,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2587",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501874400,
      "name": "__sk_mem_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234630308,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2587",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234630308,
      "name": "__sk_mem_schedule",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295270368,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2587",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295270368,
      "name": "__sk_mem_schedule",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278190012,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2587",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278190012,
      "name": "__sk_mem_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587965072,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2587",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587965072,
      "name": "__sk_mem_schedule",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587678176,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2587",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587678176,
      "name": "__sk_mem_schedule",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588296848,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2587",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588296848,
      "name": "__sk_mem_schedule",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __sk_mem_schedule(struct sock * sk, int size, int kind)
```

```json
{
  "name": "__sk_mem_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588432016,
      "name": "__sk_mem_schedule",
      "external": true,
      "loc": "net/core/sock.c:2587",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588432016,
      "name": "__sk_mem_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
