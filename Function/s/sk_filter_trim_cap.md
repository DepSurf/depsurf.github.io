# Function: <code>sk_filter_trim_cap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586821920,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:68",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586821920,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587014848,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:69",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_filter",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587014848,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 614
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587142256,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:72",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_filter",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587142256,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587647712,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:74",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_filter",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587647712,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587965952,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:85",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_filter",
        "net/ipv4/udp.c:udp_queue_rcv_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587965952,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588109104,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:90",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588109104,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588426432,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:90",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588426432,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588631792,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:90",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588631792,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589509824,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:90",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589509824,
      "name": "sk_filter_trim_cap",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589515344,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:120",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589515344,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589413024,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:120",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589413024,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590140272,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:121",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590140272,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591676288,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:122",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb_reason",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591676288,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593501552,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:124",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb_reason",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593501552,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593965328,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:124",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb_reason",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593965328,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594748096,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:129",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb_reason",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594748096,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502222824,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:90",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502222824,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234923476,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:90",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234923476,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295651200,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:90",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295651200,
      "name": "sk_filter_trim_cap",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278431026,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:90",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278431026,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588238528,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:90",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588238528,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587951344,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:90",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587951344,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588570352,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:90",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588570352,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```

```json
{
  "name": "sk_filter_trim_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588707808,
      "name": "sk_filter_trim_cap",
      "external": true,
      "loc": "net/core/filter.c:90",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588707808,
      "name": "sk_filter_trim_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int sk_filter_trim_cap(struct sock * sk, struct sk_buff * skb, unsigned int cap)
```
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
