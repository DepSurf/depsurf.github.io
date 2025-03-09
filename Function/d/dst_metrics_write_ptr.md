# Function: <code>dst_metrics_write_ptr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586915837,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:136",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_ok",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587056223,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:136",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_mtu_change_route",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:icmp6_dst_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587077541,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:136",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587100012,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:136",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587364433,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:133",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_ok",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587506527,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:133",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_mtu_change_route",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587528453,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:133",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587557510,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:133",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587567281,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:133",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_ok",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587710678,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:133",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_mtu_change_route",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587732805,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:133",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587762140,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:133",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 * dst_metrics_write_ptr(struct dst_entry * dst)
```

```json
{
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587707164,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:137",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_ok",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587859034,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:137",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_mtu_change_route",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587887013,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:137",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587920932,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:137",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587920932,
      "name": "dst_metrics_write_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
u32 * dst_metrics_write_ptr(struct dst_entry * dst)
```

```json
{
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588233860,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:139",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_ok",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588390282,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:139",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_mtu_change_route",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588421194,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:139",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588456148,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:139",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456148,
      "name": "dst_metrics_write_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588588870,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:122",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_ok",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588752285,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:122",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_mtu_change_route",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:ip6_blackhole_route"
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
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588816241,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:122",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588971837,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:122",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_mtu_change_route",
        "net/ipv6/route.c:rt6_mtu_change_route",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_blackhole_route"
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
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589250085,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589415213,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_blackhole_route"
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
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589475357,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589639453,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_blackhole_route"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590441777,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:110",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_ok",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_ok",
        "net/xfrm/xfrm_policy.c:xfrm_init_pmtu",
        "net/xfrm/xfrm_policy.c:xfrm_init_pmtu",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590677555,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:110",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_blackhole_route"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590499873,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:110",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_ok",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_ok",
        "net/xfrm/xfrm_policy.c:xfrm_init_pmtu",
        "net/xfrm/xfrm_policy.c:xfrm_init_pmtu",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590737992,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:110",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_blackhole_route"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590428700,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_ok",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_ok",
        "net/xfrm/xfrm_policy.c:xfrm_init_pmtu",
        "net/xfrm/xfrm_policy.c:xfrm_init_pmtu",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590663204,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_blackhole_route"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591227387,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_ok",
        "net/xfrm/xfrm_policy.c:xfrm_init_pmtu",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591478628,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:ip6_blackhole_route"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592890335,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:112",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_ok",
        "net/xfrm/xfrm_policy.c:xfrm_init_pmtu",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593161836,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:112",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:ip6_blackhole_route"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594770047,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:112",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_ok",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:dst_copy_metrics"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595059868,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:112",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:ip6_blackhole_route"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595165967,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:126",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_ok",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:dst_copy_metrics"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595453135,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:126",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:dst_copy_metrics"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596009074,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:126",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_bundle_ok",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:dst_copy_metrics"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596295241,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:126",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:dst_copy_metrics"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503133300,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503335556,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_blackhole_route"
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
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235813852,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3235991224,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_blackhole_route"
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
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296853644,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297086904,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:ip6_blackhole_route"
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
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279179868,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279340108,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_blackhole_route"
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
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589079725,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589243821,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_blackhole_route"
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
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588703384,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/ipv4/ip_tunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel.c:tnl_update_pmtu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588804765,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588968813,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_blackhole_route"
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
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589516589,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589680685,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_blackhole_route"
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
  "name": "dst_metrics_write_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589563587,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589729837,
      "name": "dst_metrics_write_ptr",
      "external": false,
      "loc": "include/net/dst.h:111",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:rt6_do_update_pmtu",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_blackhole_route"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
u32 * dst_metrics_write_ptr(struct dst_entry * dst)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
u32 * dst_metrics_write_ptr(struct dst_entry * dst)
```
</details>
</li>
</ul>
