# Function: <code>__bpf_sk_lookup</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long unsigned int __bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588121888,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5069",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588121888,
      "name": "__bpf_sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588442032,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5290",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588442032,
      "name": "__bpf_sk_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588648544,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5299",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588648544,
      "name": "__bpf_sk_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589521077,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5426",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589528604,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5978",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589426060,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:6080",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590161001,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:6204",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:6512",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591725840,
      "name": "__bpf_sk_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071594589938,
      "name": "__bpf_sk_lookup.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:6524",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593516640,
      "name": "__bpf_sk_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071596328554,
      "name": "__bpf_sk_lookup.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
struct sock * __bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags, int sdif)
```

```json
{
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:6604",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp",
        "net/core/filter.c:bpf_tc_sk_lookup_udp",
        "net/core/filter.c:bpf_tc_sk_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593978560,
      "name": "__bpf_sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071596858584,
      "name": "__bpf_sk_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
struct sock * __bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags, int sdif)
```

```json
{
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:6694",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp",
        "net/core/filter.c:bpf_tc_sk_lookup_udp",
        "net/core/filter.c:bpf_tc_sk_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594762528,
      "name": "__bpf_sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071597783614,
      "name": "__bpf_sk_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502193336,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5299",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502193336,
      "name": "__bpf_sk_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234940672,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5299",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234940672,
      "name": "__bpf_sk_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295676528,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5299",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295676528,
      "name": "__bpf_sk_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278448298,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5299",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278448298,
      "name": "__bpf_sk_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588255280,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5299",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588255280,
      "name": "__bpf_sk_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587968096,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5299",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587968096,
      "name": "__bpf_sk_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588587104,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5299",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588587104,
      "name": "__bpf_sk_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588724592,
      "name": "__bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5299",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588724592,
      "name": "__bpf_sk_lookup.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
long unsigned int __bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
long unsigned int __bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct sock * __bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags, int sdif)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
