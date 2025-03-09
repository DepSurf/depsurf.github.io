# Function: <code>rt6_find_cached_rt</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rt6_info * rt6_find_cached_rt(struct rt6_info * rt, struct in6_addr * daddr, struct in6_addr * saddr)
```

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588395536,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1389",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588395536,
      "name": "rt6_find_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
struct rt6_info * rt6_find_cached_rt(struct fib6_info * rt, struct in6_addr * daddr, struct in6_addr * saddr)
```

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588755248,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1527",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588755248,
      "name": "rt6_find_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
struct rt6_info * rt6_find_cached_rt(struct fib6_info * rt, struct in6_addr * daddr, struct in6_addr * saddr)
```

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588975488,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1536",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588975488,
      "name": "rt6_find_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589421488,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1761",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_mtu_from_fib6",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589421488,
      "name": "rt6_find_cached_rt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589645808,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1767",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_mtu_from_fib6",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589645808,
      "name": "rt6_find_cached_rt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
struct rt6_info * rt6_find_cached_rt(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590655200,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1789",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt",
        "net/ipv6/route.c:ip6_mtu_from_fib6",
        "net/ipv6/route.c:ip6_redirect_nh_match",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590655200,
      "name": "rt6_find_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
struct rt6_info * rt6_find_cached_rt(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590714320,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1772",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt",
        "net/ipv6/route.c:ip6_mtu_from_fib6",
        "net/ipv6/route.c:ip6_redirect_nh_match",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590714320,
      "name": "rt6_find_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
struct rt6_info * rt6_find_cached_rt(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590633968,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1782",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt",
        "net/ipv6/route.c:ip6_mtu_from_fib6",
        "net/ipv6/route.c:ip6_redirect_nh_match",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590633968,
      "name": "rt6_find_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct rt6_info * rt6_find_cached_rt(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591447248,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1785",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt",
        "net/ipv6/route.c:ip6_mtu_from_fib6",
        "net/ipv6/route.c:ip6_redirect_nh_match",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591447248,
      "name": "rt6_find_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct rt6_info * rt6_find_cached_rt(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593129376,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1785",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt",
        "net/ipv6/route.c:ip6_mtu_from_fib6",
        "net/ipv6/route.c:ip6_redirect_nh_match",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593129376,
      "name": "rt6_find_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
struct rt6_info * rt6_find_cached_rt(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595025888,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1785",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt",
        "net/ipv6/route.c:ip6_mtu_from_fib6",
        "net/ipv6/route.c:ip6_redirect_nh_match",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595025888,
      "name": "rt6_find_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
struct rt6_info * rt6_find_cached_rt(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595419296,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1784",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt",
        "net/ipv6/route.c:ip6_mtu_from_fib6",
        "net/ipv6/route.c:ip6_redirect_nh_match",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595419296,
      "name": "rt6_find_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
struct rt6_info * rt6_find_cached_rt(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596261120,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1786",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt",
        "net/ipv6/route.c:ip6_mtu_from_fib6",
        "net/ipv6/route.c:ip6_redirect_nh_match",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596261120,
      "name": "rt6_find_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503328112,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1767",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_mtu_from_fib6",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503328112,
      "name": "rt6_find_cached_rt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
struct rt6_info * rt6_find_cached_rt(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236000748,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1767",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_mtu_from_fib6",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236000748,
      "name": "rt6_find_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297095264,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1767",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_mtu_from_fib6",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297095264,
      "name": "rt6_find_cached_rt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279345356,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1767",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_mtu_from_fib6",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279345356,
      "name": "rt6_find_cached_rt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589250176,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1767",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_mtu_from_fib6",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589250176,
      "name": "rt6_find_cached_rt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588975168,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1767",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_mtu_from_fib6",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588975168,
      "name": "rt6_find_cached_rt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589687040,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1767",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_mtu_from_fib6",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589687040,
      "name": "rt6_find_cached_rt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_find_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589736368,
      "name": "rt6_find_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1767",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_mtu_from_fib6",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589736368,
      "name": "rt6_find_cached_rt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct rt6_info * rt6_find_cached_rt(struct rt6_info * rt, struct in6_addr * daddr, struct in6_addr * saddr)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rt6_info * rt</code> ➡️ <code>struct fib6_info * rt</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
struct rt6_info * rt6_find_cached_rt(struct fib6_info * rt, struct in6_addr * daddr, struct in6_addr * saddr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct rt6_info * rt6_find_cached_rt(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct rt6_info * rt6_find_cached_rt(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```
</details>
</li>
</ul>
