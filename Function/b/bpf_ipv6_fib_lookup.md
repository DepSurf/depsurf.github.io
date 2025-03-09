# Function: <code>bpf_ipv6_fib_lookup</code>

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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587973808,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4286",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587973808,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1063
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588128368,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4571",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588128368,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1063
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588453840,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4720",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588453840,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1156
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588659552,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4729",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588659552,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1156
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589527296,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4856",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589527296,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1142
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589534720,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:5400",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589534720,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589431920,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:5380",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589431920,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1196
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:5504",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590158976,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1209
    },
    {
      "addr": 18446744071592702699,
      "name": "bpf_ipv6_fib_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:5813",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591720576,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1227
    },
    {
      "addr": 18446744071594589377,
      "name": "bpf_ipv6_fib_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:5827",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593508176,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1245
    },
    {
      "addr": 18446744071596327774,
      "name": "bpf_ipv6_fib_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:5891",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593982016,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1392
    },
    {
      "addr": 18446744071596858830,
      "name": "bpf_ipv6_fib_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:5968",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594766352,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1451
    },
    {
      "addr": 18446744071597783860,
      "name": "bpf_ipv6_fib_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502206584,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4729",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502206584,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 940
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234957232,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4729",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234957232,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1004
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295687360,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4729",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295687360,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1400
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278462776,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4729",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278462776,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 906
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588266288,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4729",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588266288,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1156
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587979104,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4729",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587979104,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1156
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588598112,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4729",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588598112,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1156
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv6_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588735776,
      "name": "bpf_ipv6_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4729",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_fib_lookup",
        "net/core/filter.c:bpf_xdp_fib_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588735776,
      "name": "bpf_ipv6_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1156
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
int bpf_ipv6_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```
</details>
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
