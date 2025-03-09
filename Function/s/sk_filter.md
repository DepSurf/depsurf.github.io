# Function: <code>sk_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int sk_filter(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sk_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586384464,
      "name": "sk_filter",
      "external": true,
      "loc": "net/core/filter.c:66",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/sock.c:sock_queue_rcv_skb",
        "net/core/sock.c:sk_receive_skb",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586384464,
      "name": "sk_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585453136,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:488",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586612534,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:488",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586938917,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:488",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587151823,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:488",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587424878,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:488",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587629943,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:488",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585657227,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:569",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586796934,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:569",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587134213,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:569",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587628270,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:569",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585743823,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:668",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586921286,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:668",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587264506,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:668",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587777513,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:668",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586178199,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:673",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587418614,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:673",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587783487,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:673",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588306355,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:673",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586436436,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:708",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587721173,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:708",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588125932,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:708",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588661378,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:708",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586582542,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:729",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587854197,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:729",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588308983,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:729",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588878508,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:729",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586835594,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588158357,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588706982,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589317357,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586984918,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588363653,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588930870,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589541757,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587817249,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:829",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589224133,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:829",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589822730,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:829",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590546073,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:829",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587876993,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:838",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589222808,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:838",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589859076,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:838",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590603989,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:838",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587756209,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:881",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589116584,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:881",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589762749,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:881",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590529158,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:881",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588350515,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:902",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589835112,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:902",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590521977,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:902",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591336134,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:902",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589726218,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:896",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591356403,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:896",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592130678,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:896",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593010060,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:896",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591349705,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:867",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593124547,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:867",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593952905,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:867",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594899651,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:867",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591711434,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:867",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593577283,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:867",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594329337,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:867",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595291063,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:867",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592455165,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:901",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594349763,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:901",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595129017,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:901",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596132203,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:901",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499981900,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501875284,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502524720,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503211800,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232508460,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 3234637100,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3235234808,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 3235883452,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293306736,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295280772,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296097504,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296948080,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277053612,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278196586,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278696020,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279249094,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586741926,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587970437,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588537254,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589146125,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586609142,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587683541,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588249254,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588871117,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586939478,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588302213,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588869430,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589582989,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
  "name": "sk_filter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587038528,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588437573,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589010966,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589630781,
      "name": "sk_filter",
      "external": false,
      "loc": "include/linux/filter.h:794",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int sk_filter(struct sock * sk, struct sk_buff * skb)
```
</details>
</li>
</ul>
