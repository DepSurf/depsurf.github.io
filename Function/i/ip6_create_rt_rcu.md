# Function: <code>ip6_create_rt_rcu</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rt6_info * ip6_create_rt_rcu(struct fib6_info * rt)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588757344,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1035",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588757344,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
struct rt6_info * ip6_create_rt_rcu(struct fib6_info * rt)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588978992,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1036",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588978992,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
struct rt6_info * ip6_create_rt_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1180",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589425696,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071589450430,
      "name": "ip6_create_rt_rcu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
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
struct rt6_info * ip6_create_rt_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589650032,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1186",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589650032,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
struct rt6_info * ip6_create_rt_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590659888,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1187",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590659888,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
struct rt6_info * ip6_create_rt_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590720480,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1170",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590720480,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
struct rt6_info * ip6_create_rt_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590649584,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1173",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590649584,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
struct rt6_info * ip6_create_rt_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591457680,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1173",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591457680,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
struct rt6_info * ip6_create_rt_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593139824,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1176",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593139824,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
struct rt6_info * ip6_create_rt_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595037184,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1176",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595037184,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
struct rt6_info * ip6_create_rt_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595430640,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1175",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595430640,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
struct rt6_info * ip6_create_rt_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596272000,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1177",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596272000,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
struct rt6_info * ip6_create_rt_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503325144,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1186",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503325144,
      "name": "ip6_create_rt_rcu",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rt6_info * ip6_create_rt_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235997352,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1186",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235997352,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
struct rt6_info * ip6_create_rt_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297093744,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1186",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297093744,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
struct rt6_info * ip6_create_rt_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279342414,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1186",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279342414,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
struct rt6_info * ip6_create_rt_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589254400,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1186",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589254400,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
struct rt6_info * ip6_create_rt_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588979392,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1186",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588979392,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
struct rt6_info * ip6_create_rt_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589691264,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1186",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589691264,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
struct rt6_info * ip6_create_rt_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_create_rt_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589740784,
      "name": "ip6_create_rt_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1186",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589740784,
      "name": "ip6_create_rt_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct rt6_info * ip6_create_rt_rcu(struct fib6_info * rt)
```
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
<code>struct fib6_info * rt</code>
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
