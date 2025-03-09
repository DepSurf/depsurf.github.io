# Function: <code>skb_set_owner_r</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586197232,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:1968",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586630937,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:1968",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586720481,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:1968",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587171256,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:1968",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587262387,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:1968",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void skb_set_owner_r(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586612147,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:1932",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587079701,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:1932",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_queue_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587167356,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:1932",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587624854,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:1932",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587734013,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:1932",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv"
      ],
      "caller_func": [
        "net/packet/af_packet.c:tpacket_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587712144,
      "name": "skb_set_owner_r",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586796531,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:1994",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587270567,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:1994",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_queue_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587366540,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:1994",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587829470,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:1994",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935031,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:1994",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586920879,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2018",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587402344,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2018",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_queue_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587498908,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2018",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587986717,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2018",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588103675,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2018",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587418143,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2032",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587947170,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2032",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_queue_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588021004,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2032",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588522891,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2032",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588647007,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2032",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587720728,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2035",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588297041,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2035",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_queue_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588372061,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2035",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588889109,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2035",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589014976,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2035",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587853752,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2125",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588485902,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2125",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_queue_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588562436,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2125",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589112631,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2125",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589240094,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2125",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588157947,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2131",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588893195,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2131",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588973556,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2131",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589566344,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2131",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589692146,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2131",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588363243,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589117275,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589197972,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589790488,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589923463,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589223677,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2190",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590059991,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2190",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590169910,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2190",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590520457,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2190",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:handle_nonesp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590813483,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2190",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590952126,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2190",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591081548,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2190",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_move_skb"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589222349,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2209",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589590523,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2209",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590104987,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2209",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590219062,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2209",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590580361,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2209",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:handle_nonesp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590873611,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2209",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591014708,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2209",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591154465,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2209",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589116125,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2229",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589653082,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2229",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590018535,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2229",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590133157,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2229",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590505913,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2229",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:handle_nonesp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590800661,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2229",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590947614,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2229",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591086810,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2229",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589834605,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2269",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590409667,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2269",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590789598,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2269",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590913077,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2269",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591312799,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2269",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591618770,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2269",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591783489,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2269",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591924854,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2269",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591355852,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2387",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592004913,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2387",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592423547,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2387",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592552757,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2387",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592979323,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2387",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:handle_nonesp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593309472,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2387",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593484340,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2387",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593123980,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2422",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593819054,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2422",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594276523,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2422",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594411893,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2422",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594867531,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2422",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:handle_nonesp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595214348,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2422",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595402654,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2422",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593576704,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2410",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594193708,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2410",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594663307,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2410",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594801285,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2410",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595259467,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2410",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:handle_nonesp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595610204,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2410",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595799506,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2410",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594349168,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2400",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594989166,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2400",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595467106,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2400",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595612501,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2400",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596099835,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2400",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:handle_nonesp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596458353,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2400",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596650173,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2400",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501874600,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502733220,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502817816,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503495760,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503647912,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234636536,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3235437000,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ],
      "caller_func": []
    },
    {
      "addr": 3235519504,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236147196,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 3236285588,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295280072,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296355692,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296464488,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297283644,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297462140,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278196176,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278858900,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278931788,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279469698,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279592664,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587970027,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588723659,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588804356,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589394856,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589527831,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587683131,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588435643,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588516292,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589119848,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589253895,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588301803,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589159835,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589240532,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589831720,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589969095,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
  "name": "skb_set_owner_r",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588437131,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589199803,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589281028,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589882984,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590012059,
      "name": "skb_set_owner_r",
      "external": false,
      "loc": "include/net/sock.h:2141",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
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
void skb_set_owner_r(struct sk_buff * skb, struct sock * sk)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void skb_set_owner_r(struct sk_buff * skb, struct sock * sk)
```
</details>
</li>
</ul>
