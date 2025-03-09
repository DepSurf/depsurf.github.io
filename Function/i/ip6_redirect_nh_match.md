# Function: <code>ip6_redirect_nh_match</code>

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
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
```

```json
{
  "name": "ip6_redirect_nh_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589421712,
      "name": "ip6_redirect_nh_match",
      "external": false,
      "loc": "net/ipv6/route.c:2833",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_nh_redirect_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589421712,
      "name": "ip6_redirect_nh_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
```

```json
{
  "name": "ip6_redirect_nh_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589646032,
      "name": "ip6_redirect_nh_match",
      "external": false,
      "loc": "net/ipv6/route.c:2843",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_nh_redirect_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589646032,
      "name": "ip6_redirect_nh_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
```

```json
{
  "name": "ip6_redirect_nh_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590655424,
      "name": "ip6_redirect_nh_match",
      "external": false,
      "loc": "net/ipv6/route.c:2867",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_nh_redirect_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590655424,
      "name": "ip6_redirect_nh_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
```

```json
{
  "name": "ip6_redirect_nh_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590714544,
      "name": "ip6_redirect_nh_match",
      "external": false,
      "loc": "net/ipv6/route.c:2851",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_nh_redirect_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590714544,
      "name": "ip6_redirect_nh_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
```

```json
{
  "name": "ip6_redirect_nh_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590634192,
      "name": "ip6_redirect_nh_match",
      "external": false,
      "loc": "net/ipv6/route.c:2860",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_nh_redirect_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590634192,
      "name": "ip6_redirect_nh_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
```

```json
{
  "name": "ip6_redirect_nh_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591447472,
      "name": "ip6_redirect_nh_match",
      "external": false,
      "loc": "net/ipv6/route.c:2990",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_nh_redirect_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591447472,
      "name": "ip6_redirect_nh_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
```

```json
{
  "name": "ip6_redirect_nh_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593129600,
      "name": "ip6_redirect_nh_match",
      "external": false,
      "loc": "net/ipv6/route.c:2986",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_nh_redirect_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593129600,
      "name": "ip6_redirect_nh_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
```

```json
{
  "name": "ip6_redirect_nh_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595026128,
      "name": "ip6_redirect_nh_match",
      "external": false,
      "loc": "net/ipv6/route.c:2986",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_nh_redirect_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595026128,
      "name": "ip6_redirect_nh_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
```

```json
{
  "name": "ip6_redirect_nh_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595419536,
      "name": "ip6_redirect_nh_match",
      "external": false,
      "loc": "net/ipv6/route.c:2986",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_nh_redirect_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595419536,
      "name": "ip6_redirect_nh_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
```

```json
{
  "name": "ip6_redirect_nh_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596261360,
      "name": "ip6_redirect_nh_match",
      "external": false,
      "loc": "net/ipv6/route.c:2988",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_nh_redirect_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596261360,
      "name": "ip6_redirect_nh_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
```

```json
{
  "name": "ip6_redirect_nh_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503328368,
      "name": "ip6_redirect_nh_match",
      "external": false,
      "loc": "net/ipv6/route.c:2843",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_nh_redirect_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503328368,
      "name": "ip6_redirect_nh_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
```

```json
{
  "name": "ip6_redirect_nh_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236000996,
      "name": "ip6_redirect_nh_match",
      "external": false,
      "loc": "net/ipv6/route.c:2843",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_nh_redirect_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236000996,
      "name": "ip6_redirect_nh_match",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
```

```json
{
  "name": "ip6_redirect_nh_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297095536,
      "name": "ip6_redirect_nh_match",
      "external": false,
      "loc": "net/ipv6/route.c:2843",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_nh_redirect_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297095536,
      "name": "ip6_redirect_nh_match",
      "section": ".text",
      "bind": "STB_LOCAL",
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
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
```

```json
{
  "name": "ip6_redirect_nh_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279345500,
      "name": "ip6_redirect_nh_match",
      "external": false,
      "loc": "net/ipv6/route.c:2843",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_nh_redirect_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279345500,
      "name": "ip6_redirect_nh_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
```

```json
{
  "name": "ip6_redirect_nh_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589250400,
      "name": "ip6_redirect_nh_match",
      "external": false,
      "loc": "net/ipv6/route.c:2843",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_nh_redirect_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589250400,
      "name": "ip6_redirect_nh_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
```

```json
{
  "name": "ip6_redirect_nh_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588975392,
      "name": "ip6_redirect_nh_match",
      "external": false,
      "loc": "net/ipv6/route.c:2843",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_nh_redirect_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588975392,
      "name": "ip6_redirect_nh_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
```

```json
{
  "name": "ip6_redirect_nh_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589687264,
      "name": "ip6_redirect_nh_match",
      "external": false,
      "loc": "net/ipv6/route.c:2843",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_nh_redirect_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589687264,
      "name": "ip6_redirect_nh_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
```

```json
{
  "name": "ip6_redirect_nh_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589736592,
      "name": "ip6_redirect_nh_match",
      "external": false,
      "loc": "net/ipv6/route.c:2843",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_nh_redirect_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589736592,
      "name": "ip6_redirect_nh_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
bool ip6_redirect_nh_match(const struct fib6_result * res, struct flowi6 * fl6, const struct in6_addr * gw, struct rt6_info * * ret)
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
