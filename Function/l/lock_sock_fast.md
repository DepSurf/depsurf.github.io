# Function: <code>lock_sock_fast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586191760,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:2481",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_free_datagram_locked",
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586191760,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586614320,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:2549",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_free_datagram_locked",
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586614320,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586798400,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:2576",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_free_datagram_locked",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/udp.c:skb_consume_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586798400,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586921888,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:2743",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586921888,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587413984,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:2804",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587413984,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587723488,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:2879",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587723488,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587855824,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:2828",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587855824,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588160240,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:2971",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/udp.c:skb_consume_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588160240,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588365472,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:2986",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/udp.c:skb_consume_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588365472,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589222992,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:3115",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:skb_consume_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589222992,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589231616,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:3094",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:skb_consume_udp",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_move_skbs",
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589231616,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589125072,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:3117",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:skb_consume_udp",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:__mptcp_move_skbs",
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust",
        "net/mptcp/protocol.c:mptcp_send_ack",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack",
        "net/mptcp/sockopt.c:mptcp_sockopt_sync_all",
        "net/mptcp/sockopt.c:mptcp_sockopt_sync",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589125072,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589900412,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1649",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590746588,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1649",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590879703,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1649",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590939039,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1649",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:skb_consume_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591944899,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1649",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:__mptcp_move_skbs",
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust",
        "net/mptcp/protocol.c:mptcp_subflow_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591997676,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1649",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592004151,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1649",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_sockopt_sync_all",
        "net/mptcp/sockopt.c:mptcp_sockopt_sync",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
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
  "name": "lock_sock_fast",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591430129,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1738",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592376093,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1738",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592518511,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1738",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592582751,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1738",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:skb_consume_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592987051,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1738",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:bpf_iter_unix_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593658988,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1738",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:__mptcp_move_skbs",
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593727322,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1738",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593742418,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1738",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_sockopt_sync",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
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
  "name": "lock_sock_fast",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593196317,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1754",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594225581,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1754",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594376175,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1754",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594445375,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1754",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:skb_consume_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594875435,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1754",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:bpf_iter_unix_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595589372,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1754",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:__mptcp_move_skbs",
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595662186,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1754",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale",
        "net/mptcp/pm_netlink.c:__mptcp_pm_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595678914,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1754",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_sockopt_sync",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
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
  "name": "lock_sock_fast",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593655693,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1745",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594612413,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1745",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594835135,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1745",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_destroy_sock",
        "net/ipv4/udp.c:skb_consume_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595267723,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1745",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:bpf_iter_unix_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596098401,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1745",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:__mptcp_move_skbs",
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust",
        "net/mptcp/protocol.c:mptcp_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596170868,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1745",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale",
        "net/mptcp/pm_netlink.c:__mptcp_pm_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596189362,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1745",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_sockopt_sync",
        "net/mptcp/sockopt.c:mptcp_diag_fill_info",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
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
  "name": "lock_sock_fast",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594431549,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1720",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595415917,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1720",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595645311,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1720",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_destroy_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596108571,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1720",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:bpf_iter_unix_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596965569,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1720",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:__mptcp_move_skbs",
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust",
        "net/mptcp/protocol.c:mptcp_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597029454,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1720",
      "file": "net/mptcp/diag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/diag.c:subflow_get_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597043748,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1720",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale",
        "net/mptcp/pm_netlink.c:__mptcp_pm_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597064795,
      "name": "lock_sock_fast",
      "external": false,
      "loc": "include/net/sock.h:1720",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_set_rcvlowat",
        "net/mptcp/sockopt.c:mptcp_diag_fill_info",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int",
        "net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501868488,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:2986",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/udp.c:skb_consume_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501868488,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234631844,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:2986",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/udp.c:skb_consume_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234631844,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295273600,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:2986",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_free_datagram_locked",
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/udp.c:skb_consume_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295273600,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278197320,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:2986",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/udp.c:skb_consume_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278197320,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587972256,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:2986",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/udp.c:skb_consume_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587972256,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587685360,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:2986",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/udp.c:skb_consume_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587685360,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588304032,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:2986",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/udp.c:skb_consume_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588304032,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool lock_sock_fast(struct sock * sk)
```

```json
{
  "name": "lock_sock_fast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588433568,
      "name": "lock_sock_fast",
      "external": true,
      "loc": "net/core/sock.c:2986",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_ioctl",
        "net/ipv4/udp.c:skb_consume_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588433568,
      "name": "lock_sock_fast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
bool lock_sock_fast(struct sock * sk)
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
