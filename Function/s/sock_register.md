# Function: <code>sock_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586171504,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2429",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586171504,
      "name": "sock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586592624,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2431",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586592624,
      "name": "sock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586776928,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2478",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586776928,
      "name": "sock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586894608,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2528",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586894608,
      "name": "sock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587388640,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2521",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587388640,
      "name": "sock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2642",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587710165,
      "name": "sock_register.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071587696896,
      "name": "sock_register",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2657",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587843493,
      "name": "sock_register.cold.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071587829184,
      "name": "sock_register",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2868",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588147560,
      "name": "sock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071588131152,
      "name": "sock_register",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2948",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588352824,
      "name": "sock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071588336288,
      "name": "sock_register",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2982",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589212746,
      "name": "sock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071589195488,
      "name": "sock_register",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2977",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591625616,
      "name": "sock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071589193584,
      "name": "sock_register",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2961",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591569006,
      "name": "sock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071589090496,
      "name": "sock_register",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:3034",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592692235,
      "name": "sock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071589804832,
      "name": "sock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:3110",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mctp/af_mctp.c:mctp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594577546,
      "name": "sock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071591319472,
      "name": "sock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593073168,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:3098",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mctp/af_mctp.c:mctp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593073168,
      "name": "sock_register",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593524464,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:3136",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mctp/af_mctp.c:mctp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593524464,
      "name": "sock_register",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594295696,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:3206",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init",
        "net/mctp/af_mctp.c:mctp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594295696,
      "name": "sock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501831544,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2948",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501831544,
      "name": "sock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234607380,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2948",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234607380,
      "name": "sock_register",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295225328,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2948",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295225328,
      "name": "sock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278176692,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2948",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278176692,
      "name": "sock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2948",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587959608,
      "name": "sock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071587943072,
      "name": "sock_register",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2948",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587672712,
      "name": "sock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071587656176,
      "name": "sock_register",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2948",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588291384,
      "name": "sock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071588274848,
      "name": "sock_register",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int sock_register(const struct net_proto_family * ops)
```

```json
{
  "name": "sock_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_register",
      "external": true,
      "loc": "net/socket.c:2948",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/ipv4/af_inet.c:inet_init",
        "net/unix/af_unix.c:af_unix_init",
        "net/ipv6/af_inet6.c:inet6_init",
        "net/packet/af_packet.c:packet_init",
        "net/xdp/xsk.c:xsk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588426364,
      "name": "sock_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071588403296,
      "name": "sock_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
