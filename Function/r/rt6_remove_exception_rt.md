# Function: <code>rt6_remove_exception_rt</code>

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
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588409472,
      "name": "rt6_remove_exception_rt",
      "external": true,
      "loc": "net/ipv6/route.c:1419",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588409472,
      "name": "rt6_remove_exception_rt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588755568,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1557",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588755568,
      "name": "rt6_remove_exception_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588975808,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1566",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588975808,
      "name": "rt6_remove_exception_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589423216,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1859",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589423216,
      "name": "rt6_remove_exception_rt",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589647536,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1865",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589647536,
      "name": "rt6_remove_exception_rt",
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
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590656096,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1887",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590656096,
      "name": "rt6_remove_exception_rt",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590715216,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1870",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590715216,
      "name": "rt6_remove_exception_rt",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590639888,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1880",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590639888,
      "name": "rt6_remove_exception_rt",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591453056,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1883",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591453056,
      "name": "rt6_remove_exception_rt",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593134176,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1883",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593134176,
      "name": "rt6_remove_exception_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595031280,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1883",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595031280,
      "name": "rt6_remove_exception_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595424736,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1882",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595424736,
      "name": "rt6_remove_exception_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596266608,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1884",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596266608,
      "name": "rt6_remove_exception_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503329168,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1865",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503329168,
      "name": "rt6_remove_exception_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236002564,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1865",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236002564,
      "name": "rt6_remove_exception_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297097360,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1865",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297097360,
      "name": "rt6_remove_exception_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279346720,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1865",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279346720,
      "name": "rt6_remove_exception_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589251904,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1865",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589251904,
      "name": "rt6_remove_exception_rt",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588976896,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1865",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588976896,
      "name": "rt6_remove_exception_rt",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589688768,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1865",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589688768,
      "name": "rt6_remove_exception_rt",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int rt6_remove_exception_rt(struct rt6_info * rt)
```

```json
{
  "name": "rt6_remove_exception_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589738096,
      "name": "rt6_remove_exception_rt",
      "external": false,
      "loc": "net/ipv6/route.c:1865",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_del_cached_rt",
        "net/ipv6/route.c:ip6_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589738096,
      "name": "rt6_remove_exception_rt",
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int rt6_remove_exception_rt(struct rt6_info * rt)
```
</details>
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
