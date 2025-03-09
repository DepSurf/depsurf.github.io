# Function: <code>security_sk_classify_flow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock * sk, struct flowi * fl)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582235104,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:1310",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582235104,
      "name": "security_sk_classify_flow",
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
void security_sk_classify_flow(struct sock * sk, struct flowi * fl)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582453664,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:1340",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582453664,
      "name": "security_sk_classify_flow",
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
void security_sk_classify_flow(struct sock * sk, struct flowi * fl)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582546128,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:1361",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582546128,
      "name": "security_sk_classify_flow",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock * sk, struct flowi * fl)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582631280,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2310",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582631280,
      "name": "security_sk_classify_flow",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock * sk, struct flowi * fl)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582784768,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2171",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582784768,
      "name": "security_sk_classify_flow",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock * sk, struct flowi * fl)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582986944,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:1471",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582986944,
      "name": "security_sk_classify_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void security_sk_classify_flow(struct sock * sk, struct flowi * fl)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583098512,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2231",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583098512,
      "name": "security_sk_classify_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void security_sk_classify_flow(struct sock * sk, struct flowi * fl)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583281712,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2250",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583281712,
      "name": "security_sk_classify_flow",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock * sk, struct flowi * fl)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583387616,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2289",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583387616,
      "name": "security_sk_classify_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void security_sk_classify_flow(struct sock * sk, struct flowi * fl)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583725632,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2612",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_sk_reselect_saddr",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_flow_key_init",
        "net/ipv6/datagram.c:ip6_datagram_flow_key_init",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583725632,
      "name": "security_sk_classify_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void security_sk_classify_flow(struct sock * sk, struct flowi_common * flic)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583845824,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2629",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_sk_reselect_saddr",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_flow_key_init",
        "net/ipv6/datagram.c:ip6_datagram_flow_key_init",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583845824,
      "name": "security_sk_classify_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void security_sk_classify_flow(struct sock * sk, struct flowi_common * flic)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583871664,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2692",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871664,
      "name": "security_sk_classify_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void security_sk_classify_flow(struct sock * sk, struct flowi_common * flic)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584235440,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2700",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584235440,
      "name": "security_sk_classify_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void security_sk_classify_flow(struct sock * sk, struct flowi_common * flic)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584841280,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2734",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_sk_rebuild_header",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584841280,
      "name": "security_sk_classify_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void security_sk_classify_flow(struct sock * sk, struct flowi_common * flic)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585542832,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2714",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_sk_rebuild_header",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585542832,
      "name": "security_sk_classify_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void security_sk_classify_flow(struct sock * sk, struct flowi_common * flic)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585773488,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:4722",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_sk_rebuild_header",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585773488,
      "name": "security_sk_classify_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void security_sk_classify_flow(const struct sock * sk, struct flowi_common * flic)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586022480,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:4913",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/af_inet.c:inet_sk_rebuild_header",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586022480,
      "name": "security_sk_classify_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void security_sk_classify_flow(struct sock * sk, struct flowi * fl)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495137528,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2289",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495137528,
      "name": "security_sk_classify_flow",
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
void security_sk_classify_flow(struct sock * sk, struct flowi * fl)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228525440,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2289",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228525440,
      "name": "security_sk_classify_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void security_sk_classify_flow(struct sock * sk, struct flowi * fl)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289052000,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2289",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289052000,
      "name": "security_sk_classify_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void security_sk_classify_flow(struct sock * sk, struct flowi * fl)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274388142,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2289",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274388142,
      "name": "security_sk_classify_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void security_sk_classify_flow(struct sock * sk, struct flowi * fl)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583356352,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2289",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583356352,
      "name": "security_sk_classify_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void security_sk_classify_flow(struct sock * sk, struct flowi * fl)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583293456,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2289",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583293456,
      "name": "security_sk_classify_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void security_sk_classify_flow(struct sock * sk, struct flowi * fl)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583340128,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2289",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583340128,
      "name": "security_sk_classify_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void security_sk_classify_flow(struct sock * sk, struct flowi * fl)
```

```json
{
  "name": "security_sk_classify_flow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583435312,
      "name": "security_sk_classify_flow",
      "external": true,
      "loc": "security/security.c:2289",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/ping.c:ping_v4_sendmsg",
        "net/ipv6/af_inet6.c:inet6_sk_rebuild_header",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_flow_init",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/datagram.c:ip6_datagram_dst_update",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583435312,
      "name": "security_sk_classify_flow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct flowi_common * flic</code>
</li>
<li>
<b>Param removed. </b>
<code>struct flowi * fl</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sock * sk</code> ➡️ <code>const struct sock * sk</code>
</li>
</ul>
</details>
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
