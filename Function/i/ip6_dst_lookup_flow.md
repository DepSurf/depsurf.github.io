# Function: <code>ip6_dst_lookup_flow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_dst_lookup_flow(const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586989696,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1039",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071586989696,
      "name": "ip6_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
struct dst_entry * ip6_dst_lookup_flow(const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587436528,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1046",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071587436528,
      "name": "ip6_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
struct dst_entry * ip6_dst_lookup_flow(const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587639888,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1075",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071587639888,
      "name": "ip6_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct dst_entry * ip6_dst_lookup_flow(const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587789392,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1070",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071587789392,
      "name": "ip6_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct dst_entry * ip6_dst_lookup_flow(const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588318464,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1089",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071588318464,
      "name": "ip6_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct dst_entry * ip6_dst_lookup_flow(const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588675280,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1071",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071588675280,
      "name": "ip6_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct dst_entry * ip6_dst_lookup_flow(const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588891744,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1080",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071588891744,
      "name": "ip6_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct dst_entry * ip6_dst_lookup_flow(const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589333072,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1144",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071589333072,
      "name": "ip6_dst_lookup_flow",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_dst_lookup_flow(struct net * net, const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589557280,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1147",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071589557280,
      "name": "ip6_dst_lookup_flow",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_dst_lookup_flow(struct net * net, const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590562112,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1148",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071590562112,
      "name": "ip6_dst_lookup_flow",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_dst_lookup_flow(struct net * net, const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590622032,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1187",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071590622032,
      "name": "ip6_dst_lookup_flow",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_dst_lookup_flow(struct net * net, const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590547728,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1218",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071590547728,
      "name": "ip6_dst_lookup_flow",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_dst_lookup_flow(struct net * net, const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591363200,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1197",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071591363200,
      "name": "ip6_dst_lookup_flow",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_dst_lookup_flow(struct net * net, const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593036064,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1219",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071593036064,
      "name": "ip6_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
struct dst_entry * ip6_dst_lookup_flow(struct net * net, const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594927888,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1237",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071594927888,
      "name": "ip6_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
struct dst_entry * ip6_dst_lookup_flow(struct net * net, const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595319568,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1238",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071595319568,
      "name": "ip6_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
struct dst_entry * ip6_dst_lookup_flow(struct net * net, const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596160976,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1247",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071596160976,
      "name": "ip6_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
struct dst_entry * ip6_dst_lookup_flow(struct net * net, const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503238616,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1147",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446603336503238616,
      "name": "ip6_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct dst_entry * ip6_dst_lookup_flow(struct net * net, const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235899688,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1147",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 3235899688,
      "name": "ip6_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct dst_entry * ip6_dst_lookup_flow(struct net * net, const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296970400,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1147",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 13835058055296970400,
      "name": "ip6_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct dst_entry * ip6_dst_lookup_flow(struct net * net, const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279262376,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1147",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446743936279262376,
      "name": "ip6_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct dst_entry * ip6_dst_lookup_flow(struct net * net, const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589161648,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1147",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071589161648,
      "name": "ip6_dst_lookup_flow",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_dst_lookup_flow(struct net * net, const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588886640,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1147",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071588886640,
      "name": "ip6_dst_lookup_flow",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_dst_lookup_flow(struct net * net, const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589598512,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1147",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071589598512,
      "name": "ip6_dst_lookup_flow",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_dst_lookup_flow(struct net * net, const struct sock * sk, struct flowi6 * fl6, const struct in6_addr * final_dst)
```

```json
{
  "name": "ip6_dst_lookup_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589646736,
      "name": "ip6_dst_lookup_flow",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1147",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
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
      "addr": 18446744071589646736,
      "name": "ip6_dst_lookup_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net * net</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, fl6, final_dst</code> ➡️ <code>net, sk, fl6, final_dst</code>
</li>
</ul>
</details>
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
