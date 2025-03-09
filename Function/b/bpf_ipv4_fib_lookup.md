# Function: <code>bpf_ipv4_fib_lookup</code>

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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587971312,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4182",
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
      "addr": 18446744071587971312,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588124832,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4467",
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
      "addr": 18446744071588124832,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 895
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588455008,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4605",
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
      "addr": 18446744071588455008,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1186
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588660720,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4614",
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
      "addr": 18446744071588660720,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1186
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589518800,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4740",
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
      "addr": 18446744071589518800,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1162
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589526800,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:5283",
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
      "addr": 18446744071589526800,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1226
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589424736,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:5261",
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
      "addr": 18446744071589424736,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1202
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:5385",
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
      "addr": 18446744071590154448,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1285
    },
    {
      "addr": 18446744071592702481,
      "name": "bpf_ipv4_fib_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:5694",
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
      "addr": 18446744071591714832,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1288
    },
    {
      "addr": 18446744071594589025,
      "name": "bpf_ipv4_fib_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:5708",
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
      "addr": 18446744071593501920,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1301
    },
    {
      "addr": 18446744071596327407,
      "name": "bpf_ipv4_fib_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:5758",
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
      "addr": 18446744071593975952,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1407
    },
    {
      "addr": 18446744071596858355,
      "name": "bpf_ipv4_fib_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:5832",
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
      "addr": 18446744071594760544,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1460
    },
    {
      "addr": 18446744071597783427,
      "name": "bpf_ipv4_fib_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502207528,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4614",
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
      "addr": 18446603336502207528,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1020
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234958236,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4614",
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
      "addr": 3234958236,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1080
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295688768,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4614",
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
      "addr": 13835058055295688768,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1388
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278463682,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4614",
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
      "addr": 18446743936278463682,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 956
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588267456,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4614",
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
      "addr": 18446744071588267456,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1186
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587980272,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4614",
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
      "addr": 18446744071587980272,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1186
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588599280,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4614",
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
      "addr": 18446744071588599280,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1186
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
```

```json
{
  "name": "bpf_ipv4_fib_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588736944,
      "name": "bpf_ipv4_fib_lookup",
      "external": false,
      "loc": "net/core/filter.c:4614",
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
      "addr": 18446744071588736944,
      "name": "bpf_ipv4_fib_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1213
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
int bpf_ipv4_fib_lookup(struct net * net, struct bpf_fib_lookup * params, u32 flags, bool check_mtu)
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
