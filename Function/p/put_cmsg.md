# Function: <code>put_cmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586245264,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:215",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/core/sock.c:sock_recv_errqueue",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586245264,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586669120,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:215",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586669120,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586854080,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:215",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586854080,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586977280,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:216",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586977280,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587475472,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:216",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587475472,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587780416,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:216",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587780416,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587913328,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:216",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587913328,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588221408,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:213",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/scm.c:put_cmsg_scm_timestamping",
        "net/core/scm.c:put_cmsg_scm_timestamping64",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588221408,
      "name": "put_cmsg",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588426016,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:213",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/scm.c:put_cmsg_scm_timestamping",
        "net/core/scm.c:put_cmsg_scm_timestamping64",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588426016,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589291936,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:213",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/scm.c:put_cmsg_scm_timestamping",
        "net/core/scm.c:put_cmsg_scm_timestamping64",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589291936,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589290896,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:213",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/scm.c:put_cmsg_scm_timestamping",
        "net/core/scm.c:put_cmsg_scm_timestamping64",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589290896,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589184784,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:213",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/scm.c:put_cmsg_scm_timestamping",
        "net/core/scm.c:put_cmsg_scm_timestamping64",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589184784,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589906256,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:213",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/scm.c:put_cmsg_scm_timestamping",
        "net/core/scm.c:put_cmsg_scm_timestamping64",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589906256,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591436272,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:213",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_cmsgs",
        "net/socket.c:__sock_recv_cmsgs",
        "net/socket.c:__sock_recv_cmsgs",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/scm.c:put_cmsg_scm_timestamping",
        "net/core/scm.c:put_cmsg_scm_timestamping64",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591436272,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593203168,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:213",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_cmsgs",
        "net/socket.c:__sock_recv_cmsgs",
        "net/socket.c:__sock_recv_wifi_status",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/scm.c:put_cmsg_scm_timestamping",
        "net/core/scm.c:put_cmsg_scm_timestamping64",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593203168,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593663264,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:214",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_cmsgs",
        "net/socket.c:__sock_recv_cmsgs",
        "net/socket.c:__sock_recv_wifi_status",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/scm.c:put_cmsg_scm_timestamping",
        "net/core/scm.c:put_cmsg_scm_timestamping64",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593663264,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594441280,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:220",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_cmsgs",
        "net/socket.c:__sock_recv_cmsgs",
        "net/socket.c:__sock_recv_wifi_status",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/scm.c:put_cmsg_scm_timestamping",
        "net/core/scm.c:put_cmsg_scm_timestamping64",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594441280,
      "name": "put_cmsg",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501944040,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:213",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/scm.c:put_cmsg_scm_timestamping",
        "net/core/scm.c:put_cmsg_scm_timestamping64",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501944040,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 936
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234702192,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:213",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/scm.c:put_cmsg_scm_timestamping",
        "net/core/scm.c:put_cmsg_scm_timestamping64",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234702192,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295365920,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:213",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/scm.c:put_cmsg_scm_timestamping",
        "net/core/scm.c:put_cmsg_scm_timestamping64",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295365920,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278249804,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:213",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/scm.c:put_cmsg_scm_timestamping",
        "net/core/scm.c:put_cmsg_scm_timestamping64",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278249804,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588032800,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:213",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/scm.c:put_cmsg_scm_timestamping",
        "net/core/scm.c:put_cmsg_scm_timestamping64",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588032800,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587745888,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:213",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/scm.c:put_cmsg_scm_timestamping",
        "net/core/scm.c:put_cmsg_scm_timestamping64",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587745888,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588364576,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:213",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/scm.c:put_cmsg_scm_timestamping",
        "net/core/scm.c:put_cmsg_scm_timestamping64",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588364576,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int put_cmsg(struct msghdr * msg, int level, int type, int len, void * data)
```

```json
{
  "name": "put_cmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588500144,
      "name": "put_cmsg",
      "external": true,
      "loc": "net/core/scm.c:213",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_ts_and_drops",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_recv_errqueue",
        "net/core/scm.c:put_cmsg_scm_timestamping",
        "net/core/scm.c:put_cmsg_scm_timestamping64",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/tcp.c:tcp_recv_timestamp",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl",
        "net/ipv6/datagram.c:ip6_datagram_recv_common_ctl",
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:packet_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588500144,
      "name": "put_cmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
