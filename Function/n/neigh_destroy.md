# Function: <code>neigh_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586346336,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:683",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_update",
        "net/core/neighbour.c:__neigh_create",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ip6_fib.c:fib6_age",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586346336,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586779264,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:683",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:__neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ip6_fib.c:fib6_age",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586779264,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586965824,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:684",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:__neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ip6_fib.c:fib6_age",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586965824,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587086736,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:719",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:__neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ip6_fib.c:fib6_age",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587086736,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587594096,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:719",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:__neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587594096,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:729",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:__neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587911458,
      "name": "neigh_destroy.cold.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071587902336,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:827",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588056281,
      "name": "neigh_destroy.cold.67",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588045888,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:831",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588370654,
      "name": "neigh_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588357344,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:828",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588576949,
      "name": "neigh_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588563792,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:828",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589429403,
      "name": "neigh_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589416848,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:830",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591630339,
      "name": "neigh_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589417616,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:834",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591573772,
      "name": "neigh_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589314032,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:829",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592700845,
      "name": "neigh_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590043184,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:874",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594587302,
      "name": "neigh_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591586640,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593366896,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:912",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593366896,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 457
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593829056,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:881",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593829056,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594610656,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:889",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594610656,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502097176,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:828",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502097176,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234845532,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:828",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_rcv",
        "net/ipv6/ndisc.c:ndisc_rcv",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234845532,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295555040,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:828",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295555040,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278369438,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:828",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278369438,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:828",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588183685,
      "name": "neigh_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588170528,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:828",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/vxlan.c:route_shortcircuit",
        "drivers/net/vxlan.c:neigh_reduce",
        "drivers/net/vxlan.c:neigh_reduce",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/ip_tunnel.c:ip_tunnel_xmit",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587896517,
      "name": "neigh_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071587883360,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:828",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588515509,
      "name": "neigh_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588502352,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void neigh_destroy(struct neighbour * neigh)
```

```json
{
  "name": "neigh_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_destroy",
      "external": true,
      "loc": "net/core/neighbour.c:828",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588652741,
      "name": "neigh_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588639328,
      "name": "neigh_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
