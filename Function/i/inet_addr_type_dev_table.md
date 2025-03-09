# Function: <code>inet_addr_type_dev_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586817120,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:267",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_frontend.c:fib_del_ifaddr",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586817120,
      "name": "inet_addr_type_dev_table",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587267376,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:268",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/fib_frontend.c:fib_del_ifaddr",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587267376,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587468304,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:260",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/fib_frontend.c:fib_del_ifaddr",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587468304,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587604816,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:260",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_frontend.c:fib_del_ifaddr",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587604816,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588128896,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:270",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_frontend.c:fib_del_ifaddr",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588128896,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588485120,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:270",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_frontend.c:fib_del_ifaddr",
        "net/ipv4/fib_semantics.c:fib_check_nh",
        "net/ipv4/netfilter.c:ip_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588485120,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588679776,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:270",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_frontend.c:fib_del_ifaddr",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588679776,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589088640,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:269",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_frontend.c:fib_del_ifaddr",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589088640,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589312800,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:270",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_frontend.c:fib_del_ifaddr",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589312800,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590299171,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:260",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_del_ifaddr"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590293632,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590352176,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:260",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_del_ifaddr"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590346592,
      "name": "inet_addr_type_dev_table",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590268144,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:260",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_del_ifaddr"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590262384,
      "name": "inet_addr_type_dev_table",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591052832,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:260",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_del_ifaddr"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591047024,
      "name": "inet_addr_type_dev_table",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592701823,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:261",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_del_ifaddr"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592695616,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594571330,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:261",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_del_ifaddr"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594564832,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594963161,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:261",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_del_ifaddr"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594956656,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595775657,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:261",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_del_ifaddr"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595769136,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502949968,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:270",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_frontend.c:fib_del_ifaddr",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502949968,
      "name": "inet_addr_type_dev_table",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235643476,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:270",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_frontend.c:fib_del_ifaddr",
        "net/ipv4/fib_semantics.c:fib_check_nh",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235643476,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296623824,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:270",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_frontend.c:fib_del_ifaddr",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296623824,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279033038,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:270",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_frontend.c:fib_del_ifaddr",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279033038,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588918976,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:270",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_frontend.c:fib_del_ifaddr",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588918976,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588630912,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:270",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_frontend.c:fib_del_ifaddr",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588630912,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589355360,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:270",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_frontend.c:fib_del_ifaddr",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589355360,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
unsigned int inet_addr_type_dev_table(struct net * net, const struct net_device * dev, __be32 addr)
```

```json
{
  "name": "inet_addr_type_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589397888,
      "name": "inet_addr_type_dev_table",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:270",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_solicit",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/fib_frontend.c:fib_del_ifaddr",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/af_inet6.c:__inet6_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589397888,
      "name": "inet_addr_type_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
