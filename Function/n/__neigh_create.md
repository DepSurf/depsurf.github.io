# Function: <code>__neigh_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586352512,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:451",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_event_ns",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_xmit",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586352512,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1411
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
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586785376,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:451",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586785376,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1405
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
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586971952,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:452",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586971952,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1405
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
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587096496,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:487",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587096496,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1460
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
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587598368,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:487",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587598368,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1508
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
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:489",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_event_ns",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587911517,
      "name": "__neigh_create.cold.60",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587907088,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588054084,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:667",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588053632,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588368174,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:671",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588367712,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588574622,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:668",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588574160,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589427046,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:668",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589426464,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589427766,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:670",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589427184,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589325126,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:674",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589324544,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590054609,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:674",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_out_neigh_v6",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590053984,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591598967,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:719",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_out_neigh_v6",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591598304,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593380023,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:757",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_out_neigh_v6",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593379328,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593842181,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:726",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_out_neigh_v6",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593841504,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594623845,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:734",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_out_neigh_v6",
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594623168,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502118844,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:668",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502118272,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234863992,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:668",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234863484,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295578148,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:668",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295577456,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278384146,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:668",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278383680,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588181358,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:668",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588180896,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587894190,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:668",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587893728,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588513182,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:668",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588512720,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct neighbour * __neigh_create(struct neigh_table * tbl, const void * pkey, struct net_device * dev, bool want_ref)
```

```json
{
  "name": "__neigh_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588650414,
      "name": "__neigh_create",
      "external": true,
      "loc": "net/core/neighbour.c:668",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_event_ns"
      ],
      "caller_func": [
        "net/ipv4/route.c:__ip_do_redirect",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/route.c:ipv4_neigh_lookup",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_req_set",
        "net/ipv4/arp.c:arp_process",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588649952,
      "name": "__neigh_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
