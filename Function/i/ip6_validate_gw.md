# Function: <code>ip6_validate_gw</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588769804,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:2858",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_info_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588989984,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:2835",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_info_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589440560,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:3290",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589664939,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:3300",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ip6_validate_gw(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590675024,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:3326",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590675024,
      "name": "ip6_validate_gw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 594
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
int ip6_validate_gw(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590735376,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:3310",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590735376,
      "name": "ip6_validate_gw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 637
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
int ip6_validate_gw(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590660528,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:3320",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590660528,
      "name": "ip6_validate_gw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 707
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
int ip6_validate_gw(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591475904,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:3432",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591475904,
      "name": "ip6_validate_gw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 707
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
int ip6_validate_gw(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593158960,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:3422",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593158960,
      "name": "ip6_validate_gw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 735
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
int ip6_validate_gw(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595056880,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:3422",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595056880,
      "name": "ip6_validate_gw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 735
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595450240,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:3416",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595450240,
      "name": "ip6_validate_gw.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 735
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596292368,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:3418",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596292368,
      "name": "ip6_validate_gw.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 735
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503351068,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:3300",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236017588,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:3300",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297116600,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:3300",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279359016,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:3300",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589269307,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:3300",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588994299,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:3300",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589706171,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:3300",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_validate_gw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589756025,
      "name": "ip6_validate_gw",
      "external": false,
      "loc": "net/ipv6/route.c:3300",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ip6_validate_gw(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev, struct netlink_ext_ack * extack)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int ip6_validate_gw(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev, struct netlink_ext_ack * extack)
```
</details>
</li>
</ul>
