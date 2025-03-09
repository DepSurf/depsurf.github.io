# Function: <code>sock_i_uid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586185952,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:1721",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:ip6_dgram_sock_seq_show",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586185952,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586606512,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:1750",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:ip6_dgram_sock_seq_show",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586606512,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586790960,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:1748",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:ip6_dgram_sock_seq_show",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586790960,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586914816,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:1887",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586914816,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587406736,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:1898",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587406736,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587710208,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:1918",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587710208,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587843536,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:1914",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587843536,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588147808,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:2055",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588147808,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588353072,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:2068",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588353072,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589212800,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:2177",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_reuseport_add_sock",
        "net/ipv4/inet_hashtables.c:inet_reuseport_add_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_openreq4",
        "net/ipv4/raw.c:raw_sock_seq_show",
        "net/ipv4/udp.c:udp4_format_sock",
        "net/ipv4/udp.c:udp_reuseport_add_sock",
        "net/ipv4/udp.c:udp_reuseport_add_sock",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_format_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_openreq6",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589212800,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589211760,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:2169",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_reuseport_add_sock",
        "net/ipv4/inet_hashtables.c:inet_reuseport_add_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_openreq4",
        "net/ipv4/raw.c:raw_sock_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/ipv4/udp.c:udp4_format_sock",
        "net/ipv4/udp.c:udp_reuseport_add_sock",
        "net/ipv4/udp.c:udp_reuseport_add_sock",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_format_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_openreq6",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589211760,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589105296,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:2192",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589105296,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589823024,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:2316",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589823024,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591344192,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:2483",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:bpf_iter_unix_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591344192,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593099824,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:2562",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_bind_conflict",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:bpf_iter_unix_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593099824,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593552032,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:2611",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_bind_conflict",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:bpf_iter_unix_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593552032,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594324368,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:2591",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse",
        "net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_bind_conflict",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:bpf_iter_udp_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/unix/af_unix.c:bpf_iter_unix_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594324368,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501868928,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:2068",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501868928,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234625296,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:2068",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234625296,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295262240,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:2068",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295262240,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278184858,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:2068",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278184858,
      "name": "sock_i_uid",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587959856,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:2068",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587959856,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587672960,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:2068",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587672960,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588291632,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:2068",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588291632,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
kuid_t sock_i_uid(struct sock * sk)
```

```json
{
  "name": "sock_i_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588426704,
      "name": "sock_i_uid",
      "external": true,
      "loc": "net/core/sock.c:2068",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/raw.c:raw_seq_show",
        "net/ipv4/udp.c:udp4_seq_show",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/udp.c:udp_lib_lport_inuse",
        "net/ipv4/ping.c:ping_v4_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/datagram.c:__ip6_dgram_sock_seq_show",
        "net/packet/af_packet.c:packet_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588426704,
      "name": "sock_i_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
