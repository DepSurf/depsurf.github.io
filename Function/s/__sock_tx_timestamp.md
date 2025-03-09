# Function: <code>__sock_tx_timestamp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __sock_tx_timestamp(const struct sock * sk, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586166448,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:589",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586166448,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586586896,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:590",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586586896,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586771232,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:616",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586771232,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586894112,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:614",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586894112,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587385632,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:619",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587385632,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587688736,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:623",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587688736,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587821008,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:603",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_setup_cork",
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587821008,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588124240,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:614",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_setup_cork",
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588124240,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588329040,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:614",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_setup_cork",
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588329040,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589189696,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:629",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_setup_cork",
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589189696,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589188144,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:629",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_setup_cork",
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589188144,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589082240,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:631",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_setup_cork",
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589082240,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589801264,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:681",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_setup_cork",
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589801264,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591318848,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:682",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_setup_cork",
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591318848,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593072544,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:684",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_setup_cork",
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593072544,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593523824,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:689",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593523824,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594295120,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:691",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594295120,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501824080,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:614",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_setup_cork",
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501824080,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234606812,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:614",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_setup_cork",
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234606812,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295224160,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:614",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_setup_cork",
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295224160,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278169692,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:614",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_setup_cork",
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278169692,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587935824,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:614",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_setup_cork",
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587935824,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587648928,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:614",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_setup_cork",
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587648928,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588267600,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:614",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_setup_cork",
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588267600,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __sock_tx_timestamp(__u16 tsflags, __u8 * tx_flags)
```

```json
{
  "name": "__sock_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588402768,
      "name": "__sock_tx_timestamp",
      "external": true,
      "loc": "net/socket.c:614",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_setup_cork",
        "net/ipv4/tcp.c:tcp_tx_timestamp",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588402768,
      "name": "__sock_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>__u16 tsflags</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct sock * sk</code>
</li>
</ul>
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
