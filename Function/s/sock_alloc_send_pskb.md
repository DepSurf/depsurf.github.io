# Function: <code>sock_alloc_send_pskb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586194928,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:1841",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586194928,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586617376,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:1870",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586617376,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586801472,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:1868",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586801472,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586925328,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2007",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586925328,
      "name": "sock_alloc_send_pskb",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587417424,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2045",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587417424,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587720000,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2065",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587720000,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587853072,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2061",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587853072,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588157280,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2202",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588157280,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588362576,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2217",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588362576,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589224512,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2326",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589224512,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589221392,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2318",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589221392,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589114944,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2341",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589114944,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589833424,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2465",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589833424,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591356912,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2634",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/xdp/xsk.c:xsk_generic_xmit",
        "net/xdp/xsk.c:xsk_build_skb_zerocopy",
        "net/mctp/af_mctp.c:mctp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591356912,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593111616,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2713",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:queue_oob",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/xdp/xsk.c:__xsk_generic_xmit",
        "net/xdp/xsk.c:xsk_build_skb_zerocopy",
        "net/mctp/af_mctp.c:mctp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593111616,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593566768,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2773",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:queue_oob",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/xdp/xsk.c:__xsk_generic_xmit",
        "net/xdp/xsk.c:xsk_build_skb_zerocopy",
        "net/mctp/af_mctp.c:mctp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593566768,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594339360,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2753",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:queue_oob",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/xdp/xsk.c:xsk_build_skb",
        "net/xdp/xsk.c:xsk_build_skb_zerocopy",
        "net/mctp/af_mctp.c:mctp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594339360,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501867416,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2217",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501867416,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234635652,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2217",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234635652,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295278112,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2217",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295278112,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278195438,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2217",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278195438,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587969360,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2217",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587969360,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587682464,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2217",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587682464,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588301136,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2217",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588301136,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
struct sk_buff * sock_alloc_send_pskb(struct sock * sk, long unsigned int header_len, long unsigned int data_len, int noblock, int * errcode, int max_page_order)
```

```json
{
  "name": "sock_alloc_send_pskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588436464,
      "name": "sock_alloc_send_pskb",
      "external": true,
      "loc": "net/core/sock.c:2217",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/sock.c:sock_alloc_send_skb",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588436464,
      "name": "sock_alloc_send_pskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
