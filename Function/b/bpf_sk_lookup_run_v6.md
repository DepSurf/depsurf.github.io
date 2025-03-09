# Function: <code>bpf_sk_lookup_run_v6</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_sk_lookup_run_v6",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590797776,
      "name": "bpf_sk_lookup_run_v6",
      "external": false,
      "loc": "include/linux/filter.h:1405",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_lookup"
      ]
    },
    {
      "addr": 18446744071590982576,
      "name": "bpf_sk_lookup_run_v6",
      "external": false,
      "loc": "include/linux/filter.h:1405",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590797776,
      "name": "bpf_sk_lookup_run_v6.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
    },
    {
      "addr": 18446744071590982576,
      "name": "bpf_sk_lookup_run_v6.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_sk_lookup_run_v6",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590724432,
      "name": "bpf_sk_lookup_run_v6",
      "external": false,
      "loc": "include/linux/filter.h:1444",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_lookup"
      ]
    },
    {
      "addr": 18446744071590913248,
      "name": "bpf_sk_lookup_run_v6",
      "external": false,
      "loc": "include/linux/filter.h:1444",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590724432,
      "name": "bpf_sk_lookup_run_v6.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
    },
    {
      "addr": 18446744071590913248,
      "name": "bpf_sk_lookup_run_v6.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_sk_lookup_run_v6",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_lookup_run_v6",
      "external": false,
      "loc": "include/linux/filter.h:1468",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_lookup"
      ]
    },
    {
      "addr": 0,
      "name": "bpf_sk_lookup_run_v6",
      "external": false,
      "loc": "include/linux/filter.h:1468",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591539408,
      "name": "bpf_sk_lookup_run_v6.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
    },
    {
      "addr": 18446744071592740391,
      "name": "bpf_sk_lookup_run_v6.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071591749008,
      "name": "bpf_sk_lookup_run_v6.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
    },
    {
      "addr": 18446744071592745110,
      "name": "bpf_sk_lookup_run_v6.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_sk_lookup_run_v6",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_lookup_run_v6",
      "external": false,
      "loc": "include/linux/filter.h:1492",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_lookup"
      ]
    },
    {
      "addr": 0,
      "name": "bpf_sk_lookup_run_v6",
      "external": false,
      "loc": "include/linux/filter.h:1492",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593228848,
      "name": "bpf_sk_lookup_run_v6.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
    },
    {
      "addr": 18446744071594627053,
      "name": "bpf_sk_lookup_run_v6.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071593455200,
      "name": "bpf_sk_lookup_run_v6.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
    },
    {
      "addr": 18446744071594631677,
      "name": "bpf_sk_lookup_run_v6.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_sk_lookup_run_v6",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_lookup_run_v6",
      "external": false,
      "loc": "include/linux/filter.h:1467",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_lookup"
      ]
    },
    {
      "addr": 0,
      "name": "bpf_sk_lookup_run_v6",
      "external": false,
      "loc": "include/linux/filter.h:1467",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595128976,
      "name": "bpf_sk_lookup_run_v6.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
    },
    {
      "addr": 18446744071596360759,
      "name": "bpf_sk_lookup_run_v6.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071595372272,
      "name": "bpf_sk_lookup_run_v6.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
    },
    {
      "addr": 18446744071596364711,
      "name": "bpf_sk_lookup_run_v6.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_sk_lookup_run_v6",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_lookup_run_v6",
      "external": false,
      "loc": "include/linux/filter.h:1467",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_lookup"
      ]
    },
    {
      "addr": 0,
      "name": "bpf_sk_lookup_run_v6",
      "external": false,
      "loc": "include/linux/filter.h:1467",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595523360,
      "name": "bpf_sk_lookup_run_v6.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
    },
    {
      "addr": 18446744071596889376,
      "name": "bpf_sk_lookup_run_v6.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071595769440,
      "name": "bpf_sk_lookup_run_v6.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
    },
    {
      "addr": 18446744071596892807,
      "name": "bpf_sk_lookup_run_v6.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
bool bpf_sk_lookup_run_v6(struct net * net, int protocol, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 dport, const int ifindex, struct sock * * psk)
```

```json
{
  "name": "bpf_sk_lookup_run_v6",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_lookup_run_v6",
      "external": false,
      "loc": "include/linux/filter.h:1504",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596617584,
      "name": "bpf_sk_lookup_run_v6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
    },
    {
      "addr": 18446744071597817431,
      "name": "bpf_sk_lookup_run_v6.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
bool bpf_sk_lookup_run_v6(struct net * net, int protocol, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 dport, const int ifindex, struct sock * * psk)
```
</details>
</li>
</ul>
