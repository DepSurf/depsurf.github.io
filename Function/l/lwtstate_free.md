# Function: <code>lwtstate_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lwtstate_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586332442,
      "name": "lwtstate_free",
      "external": false,
      "loc": "include/net/lwtunnel.h:40",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586825028,
      "name": "lwtstate_free",
      "external": false,
      "loc": "include/net/lwtunnel.h:40",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lwtstate_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586765144,
      "name": "lwtstate_free",
      "external": false,
      "loc": "include/net/lwtunnel.h:40",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587275567,
      "name": "lwtstate_free",
      "external": false,
      "loc": "include/net/lwtunnel.h:40",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587075872,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:190",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587075872,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587202832,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:210",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587202832,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587717104,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:212",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587717104,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588051200,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:212",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv6/ip6_fib.c:fib6_info_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588051200,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588219488,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:212",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:free_fib_info_rcu",
        "net/ipv6/ip6_fib.c:fib6_info_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588219488,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588553760,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:207",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588553760,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588770640,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:207",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588770640,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589642560,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:209",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589642560,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589666160,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:209",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589666160,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589557872,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:209",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589557872,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590302608,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:218",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590302608,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591886864,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:218",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591886864,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593688944,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:221",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593688944,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594169728,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:221",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594169728,
      "name": "lwtstate_free",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594966272,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:221",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594966272,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502336712,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:207",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502336712,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235076428,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:207",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235076428,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295857312,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:207",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295857312,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278558778,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:207",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278558778,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588377024,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:207",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588377024,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588089712,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:207",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588089712,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588709200,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:207",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588709200,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void lwtstate_free(struct lwtunnel_state * lws)
```

```json
{
  "name": "lwtstate_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588849168,
      "name": "lwtstate_free",
      "external": true,
      "loc": "net/core/lwtunnel.c:207",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dst.c:dst_destroy",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_release",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:fib6_nh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588849168,
      "name": "lwtstate_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void lwtstate_free(struct lwtunnel_state * lws)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
