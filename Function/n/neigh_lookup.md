# Function: <code>neigh_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586340512,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:400",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_rcv",
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586340512,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586773328,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:400",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586773328,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586959872,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:401",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586959872,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587084608,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:436",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587084608,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587585904,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:436",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587585904,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587888448,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:438",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587888448,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588037776,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:524",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588037776,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588349520,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:524",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588349520,
      "name": "neigh_lookup",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588555968,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:521",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588555968,
      "name": "neigh_lookup",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589408656,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:521",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589408656,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589409536,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:523",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589409536,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589306064,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:527",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589306064,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:528",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592700595,
      "name": "neigh_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071590035520,
      "name": "neigh_lookup",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:572",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594587020,
      "name": "neigh_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071591578464,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:610",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596325811,
      "name": "neigh_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593357360,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:610",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596856048,
      "name": "neigh_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593819744,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:618",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_invalidate",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597781020,
      "name": "neigh_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071594601232,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502096888,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:521",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502096888,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234844880,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:521",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_rcv",
        "net/ipv6/ndisc.c:ndisc_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234844880,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295554112,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:521",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295554112,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278368544,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:521",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278368544,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588162704,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:521",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588162704,
      "name": "neigh_lookup",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587875536,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:521",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/vxlan.c:vxlan_xmit",
        "drivers/net/vxlan.c:route_shortcircuit",
        "drivers/net/vxlan.c:route_shortcircuit",
        "drivers/net/vxlan.c:neigh_reduce",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587875536,
      "name": "neigh_lookup",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588494528,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:521",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588494528,
      "name": "neigh_lookup",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct neighbour * neigh_lookup(struct neigh_table * tbl, const void * pkey, struct net_device * dev)
```

```json
{
  "name": "neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588631488,
      "name": "neigh_lookup",
      "external": true,
      "loc": "net/core/neighbour.c:521",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv4/fib_semantics.c:fib_detect_death",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588631488,
      "name": "neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
