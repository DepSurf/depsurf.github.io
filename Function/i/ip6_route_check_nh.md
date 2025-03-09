# Function: <code>ip6_route_check_nh</code>

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
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588770226,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:2807",
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
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588990440,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:2784",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int ip6_route_check_nh(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev)
```

```json
{
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589437408,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:3236",
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
      "addr": 18446744071589437408,
      "name": "ip6_route_check_nh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
int ip6_route_check_nh(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev)
```

```json
{
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589661776,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:3246",
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
      "addr": 18446744071589661776,
      "name": "ip6_route_check_nh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
int ip6_route_check_nh(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev)
```

```json
{
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590674496,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:3272",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_validate_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590674496,
      "name": "ip6_route_check_nh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
int ip6_route_check_nh(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev)
```

```json
{
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590734848,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:3256",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_validate_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590734848,
      "name": "ip6_route_check_nh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
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
int ip6_route_check_nh(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev)
```

```json
{
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590660000,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:3266",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_validate_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590660000,
      "name": "ip6_route_check_nh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
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
int ip6_route_check_nh(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev)
```

```json
{
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591475360,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:3378",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_validate_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591475360,
      "name": "ip6_route_check_nh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
int ip6_route_check_nh(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev)
```

```json
{
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593158384,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:3368",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_validate_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593158384,
      "name": "ip6_route_check_nh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
int ip6_route_check_nh(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev)
```

```json
{
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595056288,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:3368",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_validate_gw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595056288,
      "name": "ip6_route_check_nh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595449648,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:3361",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595449648,
      "name": "ip6_route_check_nh.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596291776,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:3363",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596291776,
      "name": "ip6_route_check_nh.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
int ip6_route_check_nh(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev)
```

```json
{
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503348240,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:3246",
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
      "addr": 18446603336503348240,
      "name": "ip6_route_check_nh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
int ip6_route_check_nh(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev)
```

```json
{
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236014144,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:3246",
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
      "addr": 3236014144,
      "name": "ip6_route_check_nh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
int ip6_route_check_nh(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev)
```

```json
{
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297112496,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:3246",
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
      "addr": 13835058055297112496,
      "name": "ip6_route_check_nh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
int ip6_route_check_nh(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev)
```

```json
{
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279356312,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:3246",
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
      "addr": 18446743936279356312,
      "name": "ip6_route_check_nh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int ip6_route_check_nh(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev)
```

```json
{
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589266144,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:3246",
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
      "addr": 18446744071589266144,
      "name": "ip6_route_check_nh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
int ip6_route_check_nh(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev)
```

```json
{
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588991136,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:3246",
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
      "addr": 18446744071588991136,
      "name": "ip6_route_check_nh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
int ip6_route_check_nh(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev)
```

```json
{
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589703008,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:3246",
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
      "addr": 18446744071589703008,
      "name": "ip6_route_check_nh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
int ip6_route_check_nh(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev)
```

```json
{
  "name": "ip6_route_check_nh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589752864,
      "name": "ip6_route_check_nh",
      "external": false,
      "loc": "net/ipv6/route.c:3246",
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
      "addr": 18446744071589752864,
      "name": "ip6_route_check_nh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int ip6_route_check_nh(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int ip6_route_check_nh(struct net * net, struct fib6_config * cfg, struct net_device * * _dev, struct inet6_dev * * idev)
```
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
