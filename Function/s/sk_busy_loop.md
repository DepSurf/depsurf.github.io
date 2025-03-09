# Function: <code>sk_busy_loop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586176968,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:78",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586237512,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:78",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586608646,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:78",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool sk_busy_loop(struct sock * sk, int nonblock)
```

```json
{
  "name": "sk_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586722640,
      "name": "sk_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:4967",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586722640,
      "name": "sk_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
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
bool sk_busy_loop(struct sock * sk, int nonblock)
```

```json
{
  "name": "sk_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586901024,
      "name": "sk_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:5081",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586901024,
      "name": "sk_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586896736,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:114",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586973538,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:114",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587381950,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:114",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587519615,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:114",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587388176,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:114",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587471754,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:114",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587912775,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:114",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588042429,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:114",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587694423,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:114",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587776842,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:114",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588246375,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:114",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588401518,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:114",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587824176,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:114",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587908522,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:114",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588436430,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:114",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588591390,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:114",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588126859,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588217495,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588845360,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589002421,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588331627,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588422263,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589071781,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589226821,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589195802,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589289273,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590032951,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590199915,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589193911,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589287950,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590079256,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590250421,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591126958,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_recvmsg",
        "net/xdp/xsk.c:xsk_sendmsg"
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589087319,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589181870,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589993690,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590168481,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591057343,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_recvmsg",
        "net/xdp/xsk.c:xsk_sendmsg"
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589805239,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589903358,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590766570,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590948913,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591899930,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_recvmsg",
        "net/xdp/xsk.c:xsk_sendmsg"
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591325503,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591433306,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592399324,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592586803,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593619602,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_recvmsg",
        "net/xdp/xsk.c:xsk_sendmsg"
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593078559,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593199530,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594250504,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594451923,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595551817,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593530147,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593659498,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594637208,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594843859,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596062405,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:104",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594302675,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:105",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594437434,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:105",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595440520,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:105",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595654499,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:105",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596925049,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:105",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501825828,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501939604,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502677400,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502845080,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234608300,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 3234696952,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 3235381168,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3235554188,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295227196,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295360556,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296287196,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296496620,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278172086,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278246656,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278816622,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278957896,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587938411,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588029047,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588678165,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588833205,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587651515,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587742135,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588390149,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588545141,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588270187,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588360823,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589114341,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589269381,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
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
  "name": "sk_busy_loop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588405467,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588496375,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589154165,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589303163,
      "name": "sk_busy_loop",
      "external": false,
      "loc": "include/net/busy_poll.h:102",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
bool sk_busy_loop(struct sock * sk, int nonblock)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
bool sk_busy_loop(struct sock * sk, int nonblock)
```
</details>
</li>
</ul>
