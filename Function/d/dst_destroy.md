# Function: <code>dst_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586332272,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:248",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_gc_task",
        "net/core/dst.c:dst_destroy_rcu",
        "net/ipv4/route.c:dst_rcu_free",
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_flo_delete",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/ipv6/route.c:ip6_dst_alloc",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:icmp6_dst_gc",
        "net/ipv6/route.c:ip6_route_add",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/ip6_fib.c:dst_rcu_free",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586332272,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586764992,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:248",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy_rcu",
        "net/core/dst.c:dst_gc_task",
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:dst_rcu_free",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_flo_delete",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:ip6_route_add",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_gc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_dst_alloc",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:dst_rcu_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586764992,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586951568,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:248",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy_rcu",
        "net/core/dst.c:dst_gc_task",
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:dst_rcu_free",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_flo_delete",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:ip6_route_add",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_gc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_dst_alloc",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:dst_rcu_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586951568,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587076432,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:117",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587076432,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587578624,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:117",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587578624,
      "name": "dst_destroy",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587887632,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:115",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587887632,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588028832,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:115",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588028832,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588342016,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:103",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588342016,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588548448,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:103",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588548448,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589399328,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:103",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589399328,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589400272,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:103",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589400272,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589297472,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:103",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589297472,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590025584,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:102",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590025584,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591566768,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:102",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591566768,
      "name": "dst_destroy",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593345792,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:102",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593345792,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593808032,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:99",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy_rcu",
        "net/core/dst.c:dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593808032,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594589472,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:99",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy_rcu",
        "net/core/dst.c:dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594589472,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502087168,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:103",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502087168,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234835564,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:103",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234835564,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295538976,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:103",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295538976,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278360082,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:103",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278360082,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588155184,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:103",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588155184,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587868016,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:103",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587868016,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588487008,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:103",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588487008,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct dst_entry * dst_destroy(struct dst_entry * dst)
```

```json
{
  "name": "dst_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588623920,
      "name": "dst_destroy",
      "external": true,
      "loc": "net/core/dst.c:103",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588623920,
      "name": "dst_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
