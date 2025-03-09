# Function: <code>nexthop_for_each_fib6_nh</code>

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
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
```

```json
{
  "name": "nexthop_for_each_fib6_nh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589149216,
      "name": "nexthop_for_each_fib6_nh",
      "external": true,
      "loc": "net/ipv4/nexthop.c:520",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nlmsg_size",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:rt6_age_exceptions",
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_flush_exceptions",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589149216,
      "name": "nexthop_for_each_fib6_nh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
```

```json
{
  "name": "nexthop_for_each_fib6_nh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589373328,
      "name": "nexthop_for_each_fib6_nh",
      "external": true,
      "loc": "net/ipv4/nexthop.c:522",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nlmsg_size",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:rt6_age_exceptions",
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_flush_exceptions",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589373328,
      "name": "nexthop_for_each_fib6_nh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
```

```json
{
  "name": "nexthop_for_each_fib6_nh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590359392,
      "name": "nexthop_for_each_fib6_nh",
      "external": true,
      "loc": "net/ipv4/nexthop.c:588",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nlmsg_size",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:rt6_age_exceptions",
        "net/ipv6/route.c:rt6_update_exception_stamp_rt",
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_flush_exceptions",
        "net/ipv6/route.c:__find_rr_leaf",
        "net/ipv6/route.c:rt6_device_match",
        "net/ipv6/ip6_fib.c:fib6_purge_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590359392,
      "name": "nexthop_for_each_fib6_nh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
```

```json
{
  "name": "nexthop_for_each_fib6_nh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590414368,
      "name": "nexthop_for_each_fib6_nh",
      "external": true,
      "loc": "net/ipv4/nexthop.c:716",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nlmsg_size",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:rt6_age_exceptions",
        "net/ipv6/route.c:rt6_update_exception_stamp_rt",
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_flush_exceptions",
        "net/ipv6/route.c:__find_rr_leaf",
        "net/ipv6/route.c:rt6_device_match",
        "net/ipv6/ip6_fib.c:fib6_purge_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590414368,
      "name": "nexthop_for_each_fib6_nh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
```

```json
{
  "name": "nexthop_for_each_fib6_nh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590331920,
      "name": "nexthop_for_each_fib6_nh",
      "external": true,
      "loc": "net/ipv4/nexthop.c:1225",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nlmsg_size",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:rt6_age_exceptions",
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_flush_exceptions",
        "net/ipv6/route.c:__find_rr_leaf",
        "net/ipv6/route.c:rt6_device_match",
        "net/ipv6/ip6_fib.c:fib6_purge_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590331920,
      "name": "nexthop_for_each_fib6_nh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
```

```json
{
  "name": "nexthop_for_each_fib6_nh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591119230,
      "name": "nexthop_for_each_fib6_nh",
      "external": true,
      "loc": "net/ipv4/nexthop.c:1225",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nlmsg_size",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:rt6_age_exceptions",
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_flush_exceptions",
        "net/ipv6/route.c:__find_rr_leaf",
        "net/ipv6/route.c:rt6_device_match",
        "net/ipv6/ip6_fib.c:fib6_purge_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592730109,
      "name": "nexthop_for_each_fib6_nh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591119184,
      "name": "nexthop_for_each_fib6_nh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
```

```json
{
  "name": "nexthop_for_each_fib6_nh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_for_each_fib6_nh",
      "external": true,
      "loc": "net/ipv4/nexthop.c:1226",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nlmsg_size",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:rt6_age_exceptions",
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_flush_exceptions",
        "net/ipv6/route.c:__find_rr_leaf",
        "net/ipv6/route.c:rt6_device_match",
        "net/ipv6/ip6_fib.c:fib6_purge_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594616083,
      "name": "nexthop_for_each_fib6_nh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592770768,
      "name": "nexthop_for_each_fib6_nh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
```

```json
{
  "name": "nexthop_for_each_fib6_nh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_for_each_fib6_nh",
      "external": true,
      "loc": "net/ipv4/nexthop.c:1226",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nlmsg_size",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:rt6_age_exceptions",
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_flush_exceptions",
        "net/ipv6/route.c:__find_rr_leaf",
        "net/ipv6/route.c:rt6_device_match",
        "net/ipv6/ip6_fib.c:fib6_purge_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596350920,
      "name": "nexthop_for_each_fib6_nh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071594643952,
      "name": "nexthop_for_each_fib6_nh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
```

```json
{
  "name": "nexthop_for_each_fib6_nh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_for_each_fib6_nh",
      "external": true,
      "loc": "net/ipv4/nexthop.c:1226",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nlmsg_size",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:rt6_age_exceptions",
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_flush_exceptions",
        "net/ipv6/route.c:__find_rr_leaf",
        "net/ipv6/route.c:rt6_device_match",
        "net/ipv6/ip6_fib.c:fib6_purge_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596879829,
      "name": "nexthop_for_each_fib6_nh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071595036384,
      "name": "nexthop_for_each_fib6_nh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
```

```json
{
  "name": "nexthop_for_each_fib6_nh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_for_each_fib6_nh",
      "external": true,
      "loc": "net/ipv4/nexthop.c:1249",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nlmsg_size",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:rt6_age_exceptions",
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_flush_exceptions",
        "net/ipv6/route.c:__find_rr_leaf",
        "net/ipv6/route.c:rt6_device_match",
        "net/ipv6/ip6_fib.c:fib6_purge_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597803908,
      "name": "nexthop_for_each_fib6_nh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071595849280,
      "name": "nexthop_for_each_fib6_nh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
```

```json
{
  "name": "nexthop_for_each_fib6_nh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503016184,
      "name": "nexthop_for_each_fib6_nh",
      "external": true,
      "loc": "net/ipv4/nexthop.c:522",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nlmsg_size",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:rt6_age_exceptions",
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_flush_exceptions",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503016184,
      "name": "nexthop_for_each_fib6_nh",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
```

```json
{
  "name": "nexthop_for_each_fib6_nh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235707036,
      "name": "nexthop_for_each_fib6_nh",
      "external": true,
      "loc": "net/ipv4/nexthop.c:522",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nlmsg_size",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:rt6_age_exceptions",
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_flush_exceptions",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235707036,
      "name": "nexthop_for_each_fib6_nh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
```

```json
{
  "name": "nexthop_for_each_fib6_nh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296710688,
      "name": "nexthop_for_each_fib6_nh",
      "external": true,
      "loc": "net/ipv4/nexthop.c:522",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nlmsg_size",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:rt6_age_exceptions",
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_flush_exceptions",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296710688,
      "name": "nexthop_for_each_fib6_nh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
```

```json
{
  "name": "nexthop_for_each_fib6_nh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279088382,
      "name": "nexthop_for_each_fib6_nh",
      "external": true,
      "loc": "net/ipv4/nexthop.c:522",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nlmsg_size",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:rt6_age_exceptions",
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_flush_exceptions",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279088382,
      "name": "nexthop_for_each_fib6_nh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
```

```json
{
  "name": "nexthop_for_each_fib6_nh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588979504,
      "name": "nexthop_for_each_fib6_nh",
      "external": true,
      "loc": "net/ipv4/nexthop.c:522",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nlmsg_size",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:rt6_age_exceptions",
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_flush_exceptions",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588979504,
      "name": "nexthop_for_each_fib6_nh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
```

```json
{
  "name": "nexthop_for_each_fib6_nh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588691440,
      "name": "nexthop_for_each_fib6_nh",
      "external": true,
      "loc": "net/ipv4/nexthop.c:522",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nlmsg_size",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:rt6_age_exceptions",
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_flush_exceptions",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588691440,
      "name": "nexthop_for_each_fib6_nh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
```

```json
{
  "name": "nexthop_for_each_fib6_nh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589415888,
      "name": "nexthop_for_each_fib6_nh",
      "external": true,
      "loc": "net/ipv4/nexthop.c:522",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nlmsg_size",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:rt6_age_exceptions",
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_flush_exceptions",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589415888,
      "name": "nexthop_for_each_fib6_nh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
```

```json
{
  "name": "nexthop_for_each_fib6_nh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589459424,
      "name": "nexthop_for_each_fib6_nh",
      "external": true,
      "loc": "net/ipv4/nexthop.c:522",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nlmsg_size",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:rt6_age_exceptions",
        "net/ipv6/route.c:rt6_remove_exception_rt",
        "net/ipv6/route.c:rt6_flush_exceptions",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:__find_rr_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589459424,
      "name": "nexthop_for_each_fib6_nh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int nexthop_for_each_fib6_nh(struct nexthop * nh, int (*)(struct fib6_nh *, void *) cb, void * arg)
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
