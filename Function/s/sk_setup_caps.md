# Function: <code>sk_setup_caps</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586187408,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:1604",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586187408,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586607696,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:1609",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586607696,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586792144,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:1607",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586792144,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586916000,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:1750",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586916000,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587407968,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:1761",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587407968,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587711424,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:1781",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587711424,
      "name": "sk_setup_caps",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587844560,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:1777",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587844560,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588148992,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:1909",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588148992,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588354256,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:1922",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588354256,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589213968,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:2019",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/af_inet.c:inet_sk_reselect_saddr",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589213968,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589212768,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:2011",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/af_inet.c:inet_sk_reselect_saddr",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589212768,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589106352,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:2040",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589106352,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589824080,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:2164",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589824080,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591346032,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:2312",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/af_inet.c:inet_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591346032,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593101632,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:2391",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/af_inet.c:inet_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593101632,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593558320,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:2443",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/af_inet.c:inet_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593558320,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594330992,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:2423",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/af_inet.c:inet_sk_rebuild_header",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594330992,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501859680,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:1922",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501859680,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234637140,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:1922",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234637140,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295264096,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:1922",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295264096,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278186244,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:1922",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278186244,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587961040,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:1922",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587961040,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587674144,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:1922",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587674144,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588292816,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:1922",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588292816,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void sk_setup_caps(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "sk_setup_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588427888,
      "name": "sk_setup_caps",
      "external": true,
      "loc": "net/core/sock.c:1922",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/route.c:ip6_sk_dst_store_flow",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588427888,
      "name": "sk_setup_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
