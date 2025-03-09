# Function: <code>fib_select_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, int mp_hash)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586833104,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1580",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586833104,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, int mp_hash)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587283152,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1616",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587283152,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, int mp_hash)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587484144,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1621",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587484144,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587621024,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1724",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587621024,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588145408,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1767",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588145408,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588500592,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1730",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588500592,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 770
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588695664,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1767",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588695664,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 770
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:2190",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589114101,
      "name": "fib_select_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071589113088,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 862
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589337328,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:2190",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589337328,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 885
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590316304,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:2208",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590316304,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590369536,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:2207",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590369536,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590285616,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:2210",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590285616,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:2251",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592726959,
      "name": "fib_select_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071591072112,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:2239",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594613238,
      "name": "fib_select_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071592721408,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:2245",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596348113,
      "name": "fib_select_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071594591728,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:2245",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596877151,
      "name": "fib_select_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071594983344,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:2253",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:__ip_rt_update_pmtu",
        "net/ipv4/route.c:__ip_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597801245,
      "name": "fib_select_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071595795840,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502976232,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:2190",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502976232,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 916
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235665772,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:2190",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235665772,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1036
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296659728,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:2190",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296659728,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1260
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279054770,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:2190",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279054770,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 666
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588943504,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:2190",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588943504,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 885
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588655440,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:2190",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588655440,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 885
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589379888,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:2190",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589379888,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 885
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
void fib_select_path(struct net * net, struct fib_result * res, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_select_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589422880,
      "name": "fib_select_path",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:2190",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_ipv4_fib_lookup",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589422880,
      "name": "fib_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 885
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sk_buff * skb</code>
</li>
<li>
<b>Param removed. </b>
<code>int mp_hash</code>
</li>
</ul>
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
