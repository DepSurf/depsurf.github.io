# Function: <code>nexthop_find_by_id</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
```

```json
{
  "name": "nexthop_find_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589153639,
      "name": "nexthop_find_by_id",
      "external": true,
      "loc": "net/ipv4/nexthop.c:136",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_to_nh_config"
      ],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589148016,
      "name": "nexthop_find_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
```

```json
{
  "name": "nexthop_find_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589377742,
      "name": "nexthop_find_by_id",
      "external": true,
      "loc": "net/ipv4/nexthop.c:136",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_to_nh_config"
      ],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372128,
      "name": "nexthop_find_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
```

```json
{
  "name": "nexthop_find_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590363388,
      "name": "nexthop_find_by_id",
      "external": true,
      "loc": "net/ipv4/nexthop.c:155",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_add",
        "net/ipv4/nexthop.c:nexthop_create_group",
        "net/ipv4/nexthop.c:nh_check_attr_group"
      ],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590357168,
      "name": "nexthop_find_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
```

```json
{
  "name": "nexthop_find_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590412777,
      "name": "nexthop_find_by_id",
      "external": true,
      "loc": "net/ipv4/nexthop.c:283",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nexthop_set_hw_flags",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:nexthop_create_group",
        "net/ipv4/nexthop.c:nh_check_attr_group"
      ],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590412400,
      "name": "nexthop_find_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
```

```json
{
  "name": "nexthop_find_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590329961,
      "name": "nexthop_find_by_id",
      "external": true,
      "loc": "net/ipv4/nexthop.c:573",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nexthop_res_grp_activity_update",
        "net/ipv4/nexthop.c:nexthop_bucket_set_hw_flags",
        "net/ipv4/nexthop.c:nexthop_set_hw_flags",
        "net/ipv4/nexthop.c:nexthop_find_group_resilient",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:nexthop_create_group",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers"
      ],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590328560,
      "name": "nexthop_find_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
```

```json
{
  "name": "nexthop_find_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591118132,
      "name": "nexthop_find_by_id",
      "external": true,
      "loc": "net/ipv4/nexthop.c:573",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nexthop_res_grp_activity_update",
        "net/ipv4/nexthop.c:nexthop_bucket_set_hw_flags",
        "net/ipv4/nexthop.c:nexthop_set_hw_flags",
        "net/ipv4/nexthop.c:nexthop_find_group_resilient",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:nexthop_create_group",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers"
      ],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591116304,
      "name": "nexthop_find_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
```

```json
{
  "name": "nexthop_find_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592771537,
      "name": "nexthop_find_by_id",
      "external": true,
      "loc": "net/ipv4/nexthop.c:574",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nexthop_res_grp_activity_update",
        "net/ipv4/nexthop.c:nexthop_bucket_set_hw_flags",
        "net/ipv4/nexthop.c:nexthop_set_hw_flags",
        "net/ipv4/nexthop.c:nexthop_find_group_resilient",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:nexthop_create_group",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers"
      ],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592769216,
      "name": "nexthop_find_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
```

```json
{
  "name": "nexthop_find_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594644769,
      "name": "nexthop_find_by_id",
      "external": true,
      "loc": "net/ipv4/nexthop.c:574",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nexthop_res_grp_activity_update",
        "net/ipv4/nexthop.c:nexthop_bucket_set_hw_flags",
        "net/ipv4/nexthop.c:nexthop_set_hw_flags",
        "net/ipv4/nexthop.c:nexthop_find_group_resilient",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:nexthop_create_group",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers"
      ],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594642272,
      "name": "nexthop_find_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
```

```json
{
  "name": "nexthop_find_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595037201,
      "name": "nexthop_find_by_id",
      "external": true,
      "loc": "net/ipv4/nexthop.c:574",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nexthop_res_grp_activity_update",
        "net/ipv4/nexthop.c:nexthop_bucket_set_hw_flags",
        "net/ipv4/nexthop.c:nexthop_set_hw_flags",
        "net/ipv4/nexthop.c:nexthop_find_group_resilient",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:nexthop_create_group",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers"
      ],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595034704,
      "name": "nexthop_find_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
```

```json
{
  "name": "nexthop_find_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595850097,
      "name": "nexthop_find_by_id",
      "external": true,
      "loc": "net/ipv4/nexthop.c:574",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nexthop_res_grp_activity_update",
        "net/ipv4/nexthop.c:nexthop_bucket_set_hw_flags",
        "net/ipv4/nexthop.c:nexthop_set_hw_flags",
        "net/ipv4/nexthop.c:nexthop_find_group_resilient",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:nexthop_create_group",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers"
      ],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595847600,
      "name": "nexthop_find_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
```

```json
{
  "name": "nexthop_find_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503020720,
      "name": "nexthop_find_by_id",
      "external": true,
      "loc": "net/ipv4/nexthop.c:136",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_to_nh_config"
      ],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503014672,
      "name": "nexthop_find_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
```

```json
{
  "name": "nexthop_find_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235710760,
      "name": "nexthop_find_by_id",
      "external": true,
      "loc": "net/ipv4/nexthop.c:136",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/nexthop.c:nexthop_create_group"
      ],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235704068,
      "name": "nexthop_find_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
```

```json
{
  "name": "nexthop_find_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296716604,
      "name": "nexthop_find_by_id",
      "external": true,
      "loc": "net/ipv4/nexthop.c:136",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_to_nh_config"
      ],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296708912,
      "name": "nexthop_find_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
```

```json
{
  "name": "nexthop_find_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279093160,
      "name": "nexthop_find_by_id",
      "external": true,
      "loc": "net/ipv4/nexthop.c:136",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_to_nh_config"
      ],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279087172,
      "name": "nexthop_find_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
```

```json
{
  "name": "nexthop_find_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588983918,
      "name": "nexthop_find_by_id",
      "external": true,
      "loc": "net/ipv4/nexthop.c:136",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_to_nh_config"
      ],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588978304,
      "name": "nexthop_find_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
```

```json
{
  "name": "nexthop_find_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588695854,
      "name": "nexthop_find_by_id",
      "external": true,
      "loc": "net/ipv4/nexthop.c:136",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_to_nh_config"
      ],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588690240,
      "name": "nexthop_find_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
```

```json
{
  "name": "nexthop_find_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589420302,
      "name": "nexthop_find_by_id",
      "external": true,
      "loc": "net/ipv4/nexthop.c:136",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_to_nh_config"
      ],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589414688,
      "name": "nexthop_find_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
```

```json
{
  "name": "nexthop_find_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589463886,
      "name": "nexthop_find_by_id",
      "external": true,
      "loc": "net/ipv4/nexthop.c:136",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_to_nh_config"
      ],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:inet6_rtm_delroute",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589458224,
      "name": "nexthop_find_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct nexthop * nexthop_find_by_id(struct net * net, u32 id)
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
