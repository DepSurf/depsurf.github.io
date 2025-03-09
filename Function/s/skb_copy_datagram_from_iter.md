# Function: <code>skb_copy_datagram_from_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586239312,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:443",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586239312,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586662816,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:465",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586662816,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586847904,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:485",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586847904,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586972368,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:510",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586972368,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587470576,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:511",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587470576,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587775536,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:509",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587775536,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587905936,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:544",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587905936,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:543",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588218051,
      "name": "skb_copy_datagram_from_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071588214736,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588419536,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:543",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588419536,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589284880,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:547",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589284880,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589283136,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:547",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589283136,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589177072,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:547",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589177072,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589899296,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:547",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589899296,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591428720,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:544",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591428720,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593195152,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:541",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:queue_oob",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593195152,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593654480,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:541",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:queue_oob",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593654480,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594430336,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:560",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:queue_oob",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594430336,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501935704,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:543",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501935704,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234693780,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:543",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234693780,
      "name": "skb_copy_datagram_from_iter",
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295356576,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:543",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295356576,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 824
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278244444,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:543",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278244444,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588026320,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:543",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588026320,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587739408,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:543",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587739408,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588358096,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:543",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588358096,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int skb_copy_datagram_from_iter(struct sk_buff * skb, int offset, struct iov_iter * from, int len)
```

```json
{
  "name": "skb_copy_datagram_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588493648,
      "name": "skb_copy_datagram_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:543",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588493648,
      "name": "skb_copy_datagram_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
