# Function: <code>fl6_update_dst</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587179248,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:864",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587179248,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587633264,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:940",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587633264,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587837888,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1156",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587837888,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587995008,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1158",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587995008,
      "name": "fl6_update_dst",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588531456,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1208",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588531456,
      "name": "fl6_update_dst",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588896096,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1144",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588896096,
      "name": "fl6_update_dst",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589119600,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1144",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589119600,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589572976,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1140",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589572976,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589797360,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1140",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589797360,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590819568,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1337",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590819568,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590879616,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1331",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590879616,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590808736,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1331",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590808736,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591627104,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1379",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591627104,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593320672,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1380",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593320672,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595225904,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1380",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595225904,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595622048,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1347",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595622048,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596469296,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1352",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596469296,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503502720,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1140",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503502720,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236154564,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1140",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236154564,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297292992,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1140",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297292992,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279475200,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1140",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279475200,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589401728,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1140",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589401728,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589126720,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1140",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589126720,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589838592,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1140",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589838592,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct in6_addr * fl6_update_dst(struct flowi6 * fl6, const struct ipv6_txoptions * opt, struct in6_addr * orig)
```

```json
{
  "name": "fl6_update_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589889872,
      "name": "fl6_update_dst",
      "external": true,
      "loc": "net/ipv6/exthdrs.c:1140",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_req",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589889872,
      "name": "fl6_update_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
