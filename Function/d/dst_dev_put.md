# Function: <code>dst_dev_put</code>

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
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587075360,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:163",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587075360,
      "name": "dst_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587576880,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:163",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587576880,
      "name": "dst_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587886000,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:166",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv6/ip6_fib.c:fib6_info_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587886000,
      "name": "dst_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588027760,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:166",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv6/ip6_fib.c:fib6_info_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588027760,
      "name": "dst_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588340928,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:154",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv6/route.c:fib6_nh_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588340928,
      "name": "dst_dev_put",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588547328,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:154",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv6/route.c:fib6_nh_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588547328,
      "name": "dst_dev_put",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589398176,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:154",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv6/route.c:fib6_nh_release",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589398176,
      "name": "dst_dev_put",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589399152,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:154",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv6/route.c:fib6_nh_release",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589399152,
      "name": "dst_dev_put",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589296352,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:154",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv6/route.c:fib6_nh_release",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589296352,
      "name": "dst_dev_put",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590024384,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:152",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv6/route.c:fib6_nh_release_dsts",
        "net/ipv6/route.c:fib6_nh_release",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590024384,
      "name": "dst_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591565360,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:152",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591565360,
      "name": "dst_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593343472,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:152",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593343472,
      "name": "dst_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593805744,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:149",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593805744,
      "name": "dst_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594587152,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:149",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594587152,
      "name": "dst_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502085904,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:154",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv6/route.c:fib6_nh_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502085904,
      "name": "dst_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234834632,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:154",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/fib_semantics.c:rt_fibinfo_free",
        "net/ipv6/route.c:fib6_nh_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234834632,
      "name": "dst_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295541088,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:154",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv6/route.c:fib6_nh_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295541088,
      "name": "dst_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278358712,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:154",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv6/route.c:fib6_nh_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278358712,
      "name": "dst_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588154064,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:154",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv6/route.c:fib6_nh_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588154064,
      "name": "dst_dev_put",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587866896,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:154",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv6/route.c:fib6_nh_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587866896,
      "name": "dst_dev_put",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588485888,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:154",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv6/route.c:fib6_nh_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588485888,
      "name": "dst_dev_put",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void dst_dev_put(struct dst_entry * dst)
```

```json
{
  "name": "dst_dev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588622800,
      "name": "dst_dev_put",
      "external": true,
      "loc": "net/core/dst.c:154",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/route.c:fnhe_flush_routes",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv6/route.c:fib6_nh_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588622800,
      "name": "dst_dev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void dst_dev_put(struct dst_entry * dst)
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
