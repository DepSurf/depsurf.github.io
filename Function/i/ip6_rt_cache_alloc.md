# Function: <code>ip6_rt_cache_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rt6_info * ip6_rt_cache_alloc(struct rt6_info * ort, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587051696,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:932",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587051696,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
struct rt6_info * ip6_rt_cache_alloc(struct rt6_info * ort, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587500880,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:937",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587500880,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
struct rt6_info * ip6_rt_cache_alloc(struct rt6_info * ort, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587704912,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:940",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587704912,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
struct rt6_info * ip6_rt_cache_alloc(struct rt6_info * ort, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587866336,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:962",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587866336,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
struct rt6_info * ip6_rt_cache_alloc(struct rt6_info * ort, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588393024,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1048",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588393024,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
struct rt6_info * ip6_rt_cache_alloc(struct fib6_info * ort, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588759648,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1169",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588759648,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
struct rt6_info * ip6_rt_cache_alloc(struct fib6_info * ort, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588979840,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1172",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588979840,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
struct rt6_info * ip6_rt_cache_alloc(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589427104,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1322",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589427104,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
struct rt6_info * ip6_rt_cache_alloc(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589651440,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1328",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589651440,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
struct rt6_info * ip6_rt_cache_alloc(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590665648,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1329",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590665648,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
struct rt6_info * ip6_rt_cache_alloc(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590725856,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1312",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590725856,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
struct rt6_info * ip6_rt_cache_alloc(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590650528,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1315",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590650528,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
struct rt6_info * ip6_rt_cache_alloc(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591459200,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1315",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591459200,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
struct rt6_info * ip6_rt_cache_alloc(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593141712,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1315",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593141712,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
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
struct rt6_info * ip6_rt_cache_alloc(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595039120,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1315",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595039120,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
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
struct rt6_info * ip6_rt_cache_alloc(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595432560,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1314",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595432560,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
struct rt6_info * ip6_rt_cache_alloc(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596273680,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1316",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:__ip6_rt_update_pmtu",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596273680,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
struct rt6_info * ip6_rt_cache_alloc(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503325416,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1328",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503325416,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
struct rt6_info * ip6_rt_cache_alloc(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235999524,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1328",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235999524,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
struct rt6_info * ip6_rt_cache_alloc(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297099216,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1328",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297099216,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
struct rt6_info * ip6_rt_cache_alloc(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279331454,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1328",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279331454,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
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
struct rt6_info * ip6_rt_cache_alloc(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589255808,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1328",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589255808,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
struct rt6_info * ip6_rt_cache_alloc(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588980800,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1328",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588980800,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
struct rt6_info * ip6_rt_cache_alloc(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589692672,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1328",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589692672,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
struct rt6_info * ip6_rt_cache_alloc(const struct fib6_result * res, const struct in6_addr * daddr, const struct in6_addr * saddr)
```

```json
{
  "name": "ip6_rt_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589742256,
      "name": "ip6_rt_cache_alloc",
      "external": false,
      "loc": "net/ipv6/route.c:1328",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589742256,
      "name": "ip6_rt_cache_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rt6_info * ort</code> ➡️ <code>struct fib6_info * ort</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct fib6_result * res</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fib6_info * ort</code>
</li>
</ul>
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
