# Function: <code>neigh_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586346301,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_update",
        "net/core/neighbour.c:__neigh_create",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586532361,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586757120,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_ioctl"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071586824409,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587068442,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587076061,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_age"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587095120,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_redirect"
      ],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv",
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586757120,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071587095120,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586787368,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:__neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586975113,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587213275,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071587273817,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587521171,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587526950,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_age"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587559453,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587205232,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586973944,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:__neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587169006,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587413643,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071587474905,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587725299,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587731302,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_age"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587764103,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:409",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587405632,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587098677,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:412",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:__neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587300220,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:412",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587549933,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:412",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071587611337,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:412",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587877319,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:412",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587885304,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:412",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_age"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587919948,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:412",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587541376,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587600597,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:413",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:__neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587822040,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:413",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588073501,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:413",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071588135353,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:413",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588399974,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:413",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588455110,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:413",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588064752,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587909231,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:414",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:__neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588165600,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:414",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588427009,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:414",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071588490729,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:414",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588762204,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:414",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588816193,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:414",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588418304,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588047984,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:421",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588349578,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:421",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588618993,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:421",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071588685433,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:421",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588982547,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:421",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589039089,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:421",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588610320,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588359607,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:423",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588753627,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:423",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589030827,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:423",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071589099141,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:423",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589429774,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:423",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589492388,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:423",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589022160,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588566039,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588977233,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589255371,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071589323317,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589654126,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589716228,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589246720,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589420576,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:421",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589932694,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:421",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590224554,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:421",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071590303794,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:421",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590668042,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:421",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590735571,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:421",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590222848,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589421312,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589973308,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590276426,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071590356738,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590728271,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590794563,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590274640,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589317743,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589887486,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590191129,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071590272258,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590653120,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590721582,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590189344,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590046895,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:423",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590650693,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:423",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590972521,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:423",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071591056834,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:423",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591461917,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:423",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591537982,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:423",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590970704,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591590475,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:449",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592275281,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:449",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592621516,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:449",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071592705923,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:449",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593144839,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:449",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593227079,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:449",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592614272,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593371147,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:446",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": [
        "net/core/neighbour.c:neigh_add"
      ]
    },
    {
      "addr": 18446744071594110908,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:446",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594486732,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:446",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071594575827,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:446",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595042327,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:446",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595126812,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:446",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593367376,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071594479008,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593833339,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:444",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": [
        "net/core/neighbour.c:neigh_add"
      ]
    },
    {
      "addr": 18446744071594497740,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:444",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594878134,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:444",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071594967635,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:444",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595435786,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:444",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595520860,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:444",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593829536,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071594870624,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594614939,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:442",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": [
        "net/core/neighbour.c:neigh_add"
      ]
    },
    {
      "addr": 18446744071595300672,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:442",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595689414,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:442",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071595780131,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:442",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596276890,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:442",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596364219,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:442",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594611136,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071595681984,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502105744,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502580760,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502883020,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502961092,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503339720,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503407012,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
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
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234857776,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3235287492,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 3235577860,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3235651256,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 3236006248,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 3236068540,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_rcv",
        "net/ipv6/ndisc.c:ndisc_rcv",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295572096,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296168972,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296543576,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 13835058055296639924,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297102264,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297183956,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296533200,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278380960,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278737602,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278983280,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279042812,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279351110,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279399314,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588172775,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588583617,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588861547,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071588929493,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589258494,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589320596,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588853104,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586657076,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "drivers/net/vxlan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/vxlan.c:route_shortcircuit",
        "drivers/net/vxlan.c:neigh_reduce",
        "drivers/net/vxlan.c:neigh_reduce"
      ],
      "caller_func": [
        "drivers/net/vxlan.c:vxlan_xmit",
        "drivers/net/vxlan.c:vxlan_xmit"
      ]
    },
    {
      "addr": 18446744071587885607,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588295601,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588573483,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071588641429,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588706470,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/ip_tunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel.c:ip_tunnel_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588983486,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589045588,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586626736,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588565040,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588504599,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589019793,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589297931,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071589365877,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589695358,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589757460,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589289280,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void neigh_release(struct neighbour * neigh)
```

```json
{
  "name": "neigh_release",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588641703,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589058433,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589339467,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": [
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process"
      ]
    },
    {
      "addr": 18446744071589408725,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_detect_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589745007,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589808132,
      "name": "neigh_release",
      "external": false,
      "loc": "include/net/neighbour.h:422",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589330752,
      "name": "neigh_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void neigh_release(struct neighbour * neigh)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void neigh_release(struct neighbour * neigh)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void neigh_release(struct neighbour * neigh)
```
</details>
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
