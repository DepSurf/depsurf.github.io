# Function: <code>napi_busy_loop</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587026384,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:5299",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587026384,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587523840,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:5440",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587523840,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587824496,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:5570",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587824496,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587957792,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6123",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587957792,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588272576,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6133",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588272576,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588501296,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6068",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588501296,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589372912,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6458",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372912,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg, bool prefer_busy_poll, u16 budget)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589381904,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6584",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/xdp/xsk.c:xsk_recvmsg",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589381904,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 730
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg, bool prefer_busy_poll, u16 budget)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589276144,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6705",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/xdp/xsk.c:xsk_recvmsg",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589276144,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 730
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg, bool prefer_busy_poll, u16 budget)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590004928,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6691",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/xdp/xsk.c:xsk_recvmsg",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590004928,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 730
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg, bool prefer_busy_poll, u16 budget)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591542816,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6177",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/xdp/xsk.c:xsk_recvmsg",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591542816,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 826
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg, bool prefer_busy_poll, u16 budget)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593316352,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6166",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593316352,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 826
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg, bool prefer_busy_poll, u16 budget)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593778016,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6143",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593778016,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 819
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg, bool prefer_busy_poll, u16 budget)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594558464,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6225",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594558464,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 819
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502033136,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6068",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502033136,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 712
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234785252,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6068",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_wait",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234785252,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 868
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295477808,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6068",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295477808,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 916
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278322190,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6068",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_wait",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278322190,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588108032,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6068",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588108032,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587820912,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6068",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587820912,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588439856,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6068",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588439856,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg)
```

```json
{
  "name": "napi_busy_loop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588576560,
      "name": "napi_busy_loop",
      "external": true,
      "loc": "net/core/dev.c:6068",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "net/socket.c:sock_poll",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588576560,
      "name": "napi_busy_loop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*)(void *, long unsigned int) loop_end, void * loop_end_arg)
```
</details>
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
<code>bool prefer_busy_poll</code>
</li>
<li>
<b>Param added. </b>
<code>u16 budget</code>
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
