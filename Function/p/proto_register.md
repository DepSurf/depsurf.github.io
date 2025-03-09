# Function: <code>proto_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586191872,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:2837",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udplite.c:udplite4_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586191872,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586614432,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:2905",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udplite.c:udplite4_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586614432,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586798512,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:2927",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udplite.c:udplite4_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586798512,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586922000,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3109",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udplite.c:udplite4_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586922000,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587414096,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3148",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udplite.c:udplite4_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587414096,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3257",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587731591,
      "name": "proto_register.cold.65",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071587717568,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3208",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587865815,
      "name": "proto_register.cold.64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071587850816,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3358",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588170564,
      "name": "proto_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071588154576,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3373",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588375815,
      "name": "proto_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071588359824,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3512",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mptcp/protocol.c:mptcp_proto_v6_init",
        "net/mptcp/protocol.c:mptcp_proto_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589238396,
      "name": "proto_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071589222384,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 602
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3464",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mptcp/protocol.c:mptcp_proto_v6_init",
        "net/mptcp/protocol.c:mptcp_proto_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591625668,
      "name": "proto_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071589220464,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 602
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3513",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mptcp/protocol.c:mptcp_proto_v6_init",
        "net/mptcp/protocol.c:mptcp_proto_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591569058,
      "name": "proto_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071589112672,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3639",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mptcp/protocol.c:mptcp_proto_v6_init",
        "net/mptcp/protocol.c:mptcp_proto_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592692435,
      "name": "proto_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071589831056,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3795",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mptcp/protocol.c:mptcp_proto_v6_init",
        "net/mptcp/protocol.c:mptcp_proto_init",
        "net/mctp/af_mctp.c:mctp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594577848,
      "name": "proto_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071591350080,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 627
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
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593105008,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3886",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mptcp/protocol.c:mptcp_proto_v6_init",
        "net/mptcp/protocol.c:mptcp_proto_init",
        "net/mctp/af_mctp.c:mctp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593105008,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 787
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
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593556368,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3917",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mptcp/protocol.c:mptcp_proto_v6_init",
        "net/mptcp/protocol.c:mptcp_proto_init",
        "net/mctp/af_mctp.c:mctp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593556368,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 793
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
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594329040,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3925",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mptcp/protocol.c:mptcp_proto_v6_init",
        "net/mptcp/protocol.c:mptcp_proto_init",
        "net/mctp/af_mctp.c:mctp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594329040,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 793
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
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501871584,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3373",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501871584,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234631956,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3373",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234631956,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295273824,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3373",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295273824,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 872
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
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278191874,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3373",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278191874,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3373",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587982599,
      "name": "proto_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071587966608,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3373",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587695703,
      "name": "proto_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071587679712,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3373",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588314375,
      "name": "proto_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071588298384,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int proto_register(struct proto * prot, int alloc_slab)
```

```json
{
  "name": "proto_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proto_register",
      "external": true,
      "loc": "net/core/sock.c:3373",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/udplite.c:udplite4_register",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588449592,
      "name": "proto_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071588433680,
      "name": "proto_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
