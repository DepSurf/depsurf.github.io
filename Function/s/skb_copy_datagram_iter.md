# Function: <code>skb_copy_datagram_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586238672,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:355",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586238672,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 631
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586662192,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:377",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586662192,
      "name": "skb_copy_datagram_iter",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586847280,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:397",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586847280,
      "name": "skb_copy_datagram_iter",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586969200,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:419",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586969200,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587467264,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:420",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587467264,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 653
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587772224,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:418",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/core/datagram.c:skb_copy_datagram_iter",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587772224,
      "name": "skb_copy_datagram_iter",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587909632,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:526",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587909632,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588214592,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:525",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588214592,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588419312,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:525",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588419312,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589288128,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:529",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/xfrm/espintcp.c:espintcp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg",
        "net/mptcp/protocol.c:__mptcp_recvmsg_mskq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589288128,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589286784,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:529",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/xfrm/espintcp.c:espintcp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg",
        "net/mptcp/protocol.c:__mptcp_recvmsg_mskq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589286784,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589180704,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:529",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/xfrm/espintcp.c:espintcp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589180704,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589899168,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:529",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/xfrm/espintcp.c:espintcp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589899168,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591428544,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:526",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/xfrm/espintcp.c:espintcp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mctp/af_mctp.c:mctp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591428544,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593194960,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:523",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/xfrm/espintcp.c:espintcp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mctp/af_mctp.c:mctp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593194960,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593654288,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:523",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/xfrm/espintcp.c:espintcp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mctp/af_mctp.c:mctp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593654288,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594430144,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:542",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/xfrm/espintcp.c:espintcp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mctp/af_mctp.c:mctp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594430144,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501935488,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:525",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501935488,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234693432,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:525",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234693432,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295356272,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:525",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295356272,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278244274,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:525",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278244274,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588026096,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:525",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588026096,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587739184,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:525",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587739184,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588357872,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:525",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588357872,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int skb_copy_datagram_iter(const struct sk_buff * skb, int offset, struct iov_iter * to, int len)
```

```json
{
  "name": "skb_copy_datagram_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588493392,
      "name": "skb_copy_datagram_iter",
      "external": true,
      "loc": "net/core/datagram.c:525",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/datagram.c:skb_copy_and_csum_datagram_msg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/ping.c:ping_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_actor",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588493392,
      "name": "skb_copy_datagram_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
