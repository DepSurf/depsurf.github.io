# Function: <code>ipv6_get_ifaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587036816,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1747",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036816,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587485168,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1809",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587485168,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587688960,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1857",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587688960,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587839968,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1899",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587839968,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588369392,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1923",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588369392,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588727248,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1944",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588727248,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588947056,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1960",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588947056,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589390864,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1993",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589390864,
      "name": "ipv6_get_ifaddr",
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589615440,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1995",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589615440,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590626464,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1986",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590626464,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590687152,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:2012",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590687152,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590612288,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:2014",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590612288,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591425248,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:2021",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591425248,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593103168,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:2026",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593103168,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594998864,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:2026",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594998864,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595392320,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:2025",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595392320,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596233840,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:2053",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596233840,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503296128,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1995",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503296128,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235965028,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1995",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_rcv",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235965028,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297049680,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1995",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297049680,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279314932,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1995",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279314932,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589219808,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1995",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589219808,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588944800,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1995",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588944800,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589656672,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1995",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589656672,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct inet6_ifaddr * ipv6_get_ifaddr(struct net * net, const struct in6_addr * addr, struct net_device * dev, int strict)
```

```json
{
  "name": "ipv6_get_ifaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589705728,
      "name": "ipv6_get_ifaddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1995",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589705728,
      "name": "ipv6_get_ifaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
