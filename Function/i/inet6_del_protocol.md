# Function: <code>inet6_del_protocol</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587236368,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:39",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587236368,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587701040,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:39",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587701040,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587915536,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:39",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587915536,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588073840,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:39",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588073840,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588618064,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:39",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588618064,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588984016,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:39",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588984016,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589208048,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:39",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589208048,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589661824,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:35",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589661824,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589886112,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:35",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589886112,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590915424,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:35",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590915424,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590978528,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:35",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590978528,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590909232,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:35",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590909232,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591744848,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:35",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591744848,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593450208,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:35",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593450208,
      "name": "inet6_del_protocol",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595366880,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:35",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595366880,
      "name": "inet6_del_protocol",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595764064,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:35",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595764064,
      "name": "inet6_del_protocol",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596612224,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:35",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596612224,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503607656,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:35",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503607656,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236251884,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:35",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236251884,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297420464,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:35",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297420464,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279559442,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:35",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279559442,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589490480,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:35",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589490480,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589215472,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:35",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589215472,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589931744,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:35",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589931744,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int inet6_del_protocol(const struct inet6_protocol * prot, unsigned char protocol)
```

```json
{
  "name": "inet6_del_protocol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589981152,
      "name": "inet6_del_protocol",
      "external": true,
      "loc": "net/ipv6/protocol.c:35",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_exit",
        "net/ipv6/udp.c:udpv6_init",
        "net/ipv6/udplite.c:udplitev6_exit",
        "net/ipv6/udplite.c:udplitev6_init",
        "net/ipv6/icmp.c:icmpv6_cleanup",
        "net/ipv6/icmp.c:icmpv6_init",
        "net/ipv6/reassembly.c:ipv6_frag_exit",
        "net/ipv6/reassembly.c:ipv6_frag_init",
        "net/ipv6/tcp_ipv6.c:tcpv6_exit",
        "net/ipv6/tcp_ipv6.c:tcpv6_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_exit",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/exthdrs.c:ipv6_exthdrs_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589981152,
      "name": "inet6_del_protocol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
