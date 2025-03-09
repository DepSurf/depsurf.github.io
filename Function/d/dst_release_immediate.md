# Function: <code>dst_release_immediate</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587076656,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:193",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
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
        "net/ipv6/route.c:ip6_route_add",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_dst_alloc",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587076656,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587578832,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:193",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_add",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_dst_alloc",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587578832,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:196",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587887967,
      "name": "dst_release_immediate.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071587887856,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:196",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588029742,
      "name": "dst_release_immediate.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071588029056,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:184",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588342976,
      "name": "dst_release_immediate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071588342240,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:184",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588549424,
      "name": "dst_release_immediate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071588548672,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:184",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589400493,
      "name": "dst_release_immediate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589399568,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:184",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591630215,
      "name": "dst_release_immediate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589400512,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:184",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591573648,
      "name": "dst_release_immediate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589297712,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:182",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592700315,
      "name": "dst_release_immediate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071590025792,
      "name": "dst_release_immediate",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:182",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594586750,
      "name": "dst_release_immediate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071591566992,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:182",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596325614,
      "name": "dst_release_immediate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071593346064,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593808176,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:171",
      "file": "net/core/dst.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_destroy",
        "net/core/dst.c:dst_destroy"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593808464,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594589616,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:171",
      "file": "net/core/dst.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_destroy",
        "net/core/dst.c:dst_destroy"
      ],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594589904,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502086952,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:184",
      "file": "net/core/dst.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502086952,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234835892,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:184",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:rt_fibinfo_free",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234835892,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295539408,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:184",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295539408,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278360352,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:184",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278360352,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:184",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588156160,
      "name": "dst_release_immediate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071588155408,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:184",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587868992,
      "name": "dst_release_immediate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071587868240,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:184",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588487984,
      "name": "dst_release_immediate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071588487232,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void dst_release_immediate(struct dst_entry * dst)
```

```json
{
  "name": "dst_release_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dst_release_immediate",
      "external": true,
      "loc": "net/core/dst.c:184",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588624896,
      "name": "dst_release_immediate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071588624144,
      "name": "dst_release_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void dst_release_immediate(struct dst_entry * dst)
```
</details>
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
