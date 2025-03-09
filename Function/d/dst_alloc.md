# Function: <code>dst_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586330784,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:200",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_dst_alloc",
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/ipv6/route.c:__ip6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586330784,
      "name": "dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586763520,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:200",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:__ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586763520,
      "name": "dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586950096,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:200",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:__ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586950096,
      "name": "dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587077136,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:97",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:__ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587077136,
      "name": "dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587578432,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:97",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:__ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587578432,
      "name": "dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587887424,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:95",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587887424,
      "name": "dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588029568,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:95",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588029568,
      "name": "dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588342915,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:79",
      "file": "net/core/dst.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588343006,
      "name": "dst_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071588342768,
      "name": "dst_alloc",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588549363,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:79",
      "file": "net/core/dst.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588549454,
      "name": "dst_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071588549216,
      "name": "dst_alloc",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:79",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589400520,
      "name": "dst_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589400112,
      "name": "dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:79",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591630242,
      "name": "dst_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589401056,
      "name": "dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:79",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591573675,
      "name": "dst_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589298256,
      "name": "dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:78",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592700368,
      "name": "dst_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590026432,
      "name": "dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:78",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594586804,
      "name": "dst_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071591567728,
      "name": "dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593346336,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:78",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593346336,
      "name": "dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593808608,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:79",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593808608,
      "name": "dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594590048,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:79",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc",
        "net/ipv6/route.c:ip6_create_rt_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594590048,
      "name": "dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502086736,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:79",
      "file": "net/core/dst.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502086736,
      "name": "dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234836596,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:79",
      "file": "net/core/dst.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234836596,
      "name": "dst_alloc",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295540800,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:79",
      "file": "net/core/dst.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295540800,
      "name": "dst_alloc",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278360822,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:79",
      "file": "net/core/dst.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278360822,
      "name": "dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588156099,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:79",
      "file": "net/core/dst.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588156190,
      "name": "dst_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071588155952,
      "name": "dst_alloc",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587868931,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:79",
      "file": "net/core/dst.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587869022,
      "name": "dst_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071587868784,
      "name": "dst_alloc",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588487923,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:79",
      "file": "net/core/dst.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588488014,
      "name": "dst_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071588487776,
      "name": "dst_alloc",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * dst_alloc(struct dst_ops * ops, struct net_device * dev, int initial_ref, int initial_obsolete, short unsigned int flags)
```

```json
{
  "name": "dst_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588624835,
      "name": "dst_alloc",
      "external": true,
      "loc": "net/core/dst.c:79",
      "file": "net/core/dst.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_dst_alloc",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588624926,
      "name": "dst_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071588624688,
      "name": "dst_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int initial_ref</code>
</li>
<li>
<b>Param reordered. </b>
<code>ops, dev, initial_ref, initial_obsolete, flags</code> ➡️ <code>ops, dev, initial_obsolete, flags</code>
</li>
</ul>
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
