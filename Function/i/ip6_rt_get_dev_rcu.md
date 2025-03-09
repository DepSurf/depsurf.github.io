# Function: <code>ip6_rt_get_dev_rcu</code>

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
struct net_device * ip6_rt_get_dev_rcu(struct rt6_info * rt)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588384336,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1026",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588384336,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
struct net_device * ip6_rt_get_dev_rcu(struct fib6_info * rt)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588744080,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:869",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588744080,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
struct net_device * ip6_rt_get_dev_rcu(struct fib6_info * rt)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588964288,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:871",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588964288,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
struct net_device * ip6_rt_get_dev_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589408384,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1009",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589408384,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct net_device * ip6_rt_get_dev_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589632624,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1015",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589632624,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct net_device * ip6_rt_get_dev_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590642752,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1018",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_rt_pcpu_alloc",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590642752,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
struct net_device * ip6_rt_get_dev_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590702848,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1001",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_rt_pcpu_alloc",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590702848,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
struct net_device * ip6_rt_get_dev_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590628672,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1004",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590628672,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
struct net_device * ip6_rt_get_dev_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591442144,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1004",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591442144,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
struct net_device * ip6_rt_get_dev_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593121536,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1007",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593121536,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
struct net_device * ip6_rt_get_dev_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595017920,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1007",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595017920,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
struct net_device * ip6_rt_get_dev_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595411456,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1006",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595411456,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
struct net_device * ip6_rt_get_dev_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596253152,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1008",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596253152,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
struct net_device * ip6_rt_get_dev_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503315400,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1015",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503315400,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct net_device * ip6_rt_get_dev_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235984324,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1015",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235984324,
      "name": "ip6_rt_get_dev_rcu",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct net_device * ip6_rt_get_dev_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297073696,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1015",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297073696,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
struct net_device * ip6_rt_get_dev_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279331300,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1015",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279331300,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
struct net_device * ip6_rt_get_dev_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589236992,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1015",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589236992,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct net_device * ip6_rt_get_dev_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588961984,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1015",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588961984,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct net_device * ip6_rt_get_dev_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589673856,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1015",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589673856,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct net_device * ip6_rt_get_dev_rcu(const struct fib6_result * res)
```

```json
{
  "name": "ip6_rt_get_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589722992,
      "name": "ip6_rt_get_dev_rcu",
      "external": false,
      "loc": "net/ipv6/route.c:1015",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589722992,
      "name": "ip6_rt_get_dev_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct net_device * ip6_rt_get_dev_rcu(struct rt6_info * rt)
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
