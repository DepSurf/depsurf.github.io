# Function: <code>bpf_sk_lookup_run_v4</code>

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
  "name": "bpf_sk_lookup_run_v4",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590040192,
      "name": "bpf_sk_lookup_run_v4",
      "external": false,
      "loc": "include/linux/filter.h:1369",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    },
    {
      "addr": 18446744071590242864,
      "name": "bpf_sk_lookup_run_v4",
      "external": false,
      "loc": "include/linux/filter.h:1369",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590040192,
      "name": "bpf_sk_lookup_run_v4.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
    },
    {
      "addr": 18446744071590242864,
      "name": "bpf_sk_lookup_run_v4.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
  "name": "bpf_sk_lookup_run_v4",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589954400,
      "name": "bpf_sk_lookup_run_v4",
      "external": false,
      "loc": "include/linux/filter.h:1408",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    },
    {
      "addr": 18446744071590156832,
      "name": "bpf_sk_lookup_run_v4",
      "external": false,
      "loc": "include/linux/filter.h:1408",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589954400,
      "name": "bpf_sk_lookup_run_v4.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
    },
    {
      "addr": 18446744071590156832,
      "name": "bpf_sk_lookup_run_v4.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
  "name": "bpf_sk_lookup_run_v4",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_lookup_run_v4",
      "external": false,
      "loc": "include/linux/filter.h:1432",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    },
    {
      "addr": 0,
      "name": "bpf_sk_lookup_run_v4",
      "external": false,
      "loc": "include/linux/filter.h:1432",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590721568,
      "name": "bpf_sk_lookup_run_v4.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071592714732,
      "name": "bpf_sk_lookup_run_v4.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071590937248,
      "name": "bpf_sk_lookup_run_v4.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071592722315,
      "name": "bpf_sk_lookup_run_v4.constprop.0.cold",
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
  "name": "bpf_sk_lookup_run_v4",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_lookup_run_v4",
      "external": false,
      "loc": "include/linux/filter.h:1455",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    },
    {
      "addr": 0,
      "name": "bpf_sk_lookup_run_v4",
      "external": false,
      "loc": "include/linux/filter.h:1455",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592350528,
      "name": "bpf_sk_lookup_run_v4.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071594600811,
      "name": "bpf_sk_lookup_run_v4.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071592580128,
      "name": "bpf_sk_lookup_run_v4.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071594608578,
      "name": "bpf_sk_lookup_run_v4.constprop.0.cold",
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
  "name": "bpf_sk_lookup_run_v4",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_lookup_run_v4",
      "external": false,
      "loc": "include/linux/filter.h:1430",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    },
    {
      "addr": 0,
      "name": "bpf_sk_lookup_run_v4",
      "external": false,
      "loc": "include/linux/filter.h:1430",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594189616,
      "name": "bpf_sk_lookup_run_v4.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071596336418,
      "name": "bpf_sk_lookup_run_v4.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071594442144,
      "name": "bpf_sk_lookup_run_v4.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071596343886,
      "name": "bpf_sk_lookup_run_v4.constprop.0.cold",
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
  "name": "bpf_sk_lookup_run_v4",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_lookup_run_v4",
      "external": false,
      "loc": "include/linux/filter.h:1430",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    },
    {
      "addr": 0,
      "name": "bpf_sk_lookup_run_v4",
      "external": false,
      "loc": "include/linux/filter.h:1430",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594576720,
      "name": "bpf_sk_lookup_run_v4.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
    },
    {
      "addr": 18446744071596866099,
      "name": "bpf_sk_lookup_run_v4.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071594832352,
      "name": "bpf_sk_lookup_run_v4.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
    },
    {
      "addr": 18446744071596872922,
      "name": "bpf_sk_lookup_run_v4.constprop.0.cold",
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
bool bpf_sk_lookup_run_v4(struct net * net, int protocol, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 dport, const int ifindex, struct sock * * psk)
```

```json
{
  "name": "bpf_sk_lookup_run_v4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_lookup_run_v4",
      "external": false,
      "loc": "include/linux/filter.h:1467",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_lookup_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595379984,
      "name": "bpf_sk_lookup_run_v4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
    },
    {
      "addr": 18446744071597791153,
      "name": "bpf_sk_lookup_run_v4.cold",
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
bool bpf_sk_lookup_run_v4(struct net * net, int protocol, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 dport, const int ifindex, struct sock * * psk)
```
</details>
</li>
</ul>
