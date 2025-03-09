# Function: <code>__bpf_skc_lookup</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "__bpf_skc_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588441376,
      "name": "__bpf_skc_lookup",
      "external": false,
      "loc": "net/core/filter.c:5249",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_skc_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp",
        "net/core/filter.c:bpf_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588441376,
      "name": "__bpf_skc_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "__bpf_skc_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588647904,
      "name": "__bpf_skc_lookup",
      "external": false,
      "loc": "net/core/filter.c:5258",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_skc_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp",
        "net/core/filter.c:bpf_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588647904,
      "name": "__bpf_skc_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "__bpf_skc_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589519968,
      "name": "__bpf_skc_lookup",
      "external": false,
      "loc": "net/core/filter.c:5385",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_sock_addr_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589519968,
      "name": "__bpf_skc_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "__bpf_skc_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589525440,
      "name": "__bpf_skc_lookup",
      "external": false,
      "loc": "net/core/filter.c:5937",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_sock_addr_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589525440,
      "name": "__bpf_skc_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "__bpf_skc_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589423264,
      "name": "__bpf_skc_lookup",
      "external": false,
      "loc": "net/core/filter.c:6039",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_sock_addr_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589423264,
      "name": "__bpf_skc_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
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
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "__bpf_skc_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590149792,
      "name": "__bpf_skc_lookup",
      "external": false,
      "loc": "net/core/filter.c:6163",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_sk_lookup_udp",
        "net/core/filter.c:bpf_sock_addr_sk_lookup_tcp",
        "net/core/filter.c:bpf_sock_addr_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_tcp",
        "net/core/filter.c:bpf_xdp_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590149792,
      "name": "__bpf_skc_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
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
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "__bpf_skc_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591712080,
      "name": "__bpf_skc_lookup",
      "external": false,
      "loc": "net/core/filter.c:6471",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_skc_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp",
        "net/core/filter.c:bpf_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591712080,
      "name": "__bpf_skc_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "__bpf_skc_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593498304,
      "name": "__bpf_skc_lookup",
      "external": false,
      "loc": "net/core/filter.c:6484",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_skc_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp",
        "net/core/filter.c:bpf_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593498304,
      "name": "__bpf_skc_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags, int sdif)
```

```json
{
  "name": "__bpf_skc_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593963584,
      "name": "__bpf_skc_lookup",
      "external": false,
      "loc": "net/core/filter.c:6563",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_skc_lookup_tcp",
        "net/core/filter.c:bpf_tc_skc_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp",
        "net/core/filter.c:bpf_sk_lookup",
        "net/core/filter.c:__bpf_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593963584,
      "name": "__bpf_skc_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags, int sdif)
```

```json
{
  "name": "__bpf_skc_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594745808,
      "name": "__bpf_skc_lookup",
      "external": false,
      "loc": "net/core/filter.c:6653",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_skc_lookup_tcp",
        "net/core/filter.c:bpf_tc_skc_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp",
        "net/core/filter.c:bpf_sk_lookup",
        "net/core/filter.c:__bpf_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594745808,
      "name": "__bpf_skc_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "__bpf_skc_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502192296,
      "name": "__bpf_skc_lookup",
      "external": false,
      "loc": "net/core/filter.c:5258",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_skc_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp",
        "net/core/filter.c:bpf_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502192296,
      "name": "__bpf_skc_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "__bpf_skc_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234939784,
      "name": "__bpf_skc_lookup",
      "external": false,
      "loc": "net/core/filter.c:5258",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_skc_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp",
        "net/core/filter.c:bpf_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234939784,
      "name": "__bpf_skc_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "__bpf_skc_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295675600,
      "name": "__bpf_skc_lookup",
      "external": false,
      "loc": "net/core/filter.c:5258",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_skc_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp",
        "net/core/filter.c:bpf_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295675600,
      "name": "__bpf_skc_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "__bpf_skc_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278447534,
      "name": "__bpf_skc_lookup",
      "external": false,
      "loc": "net/core/filter.c:5258",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_skc_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp",
        "net/core/filter.c:bpf_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278447534,
      "name": "__bpf_skc_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "__bpf_skc_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588254640,
      "name": "__bpf_skc_lookup",
      "external": false,
      "loc": "net/core/filter.c:5258",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_skc_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp",
        "net/core/filter.c:bpf_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588254640,
      "name": "__bpf_skc_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "__bpf_skc_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587967456,
      "name": "__bpf_skc_lookup",
      "external": false,
      "loc": "net/core/filter.c:5258",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_skc_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp",
        "net/core/filter.c:bpf_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587967456,
      "name": "__bpf_skc_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "__bpf_skc_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588586464,
      "name": "__bpf_skc_lookup",
      "external": false,
      "loc": "net/core/filter.c:5258",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_skc_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp",
        "net/core/filter.c:bpf_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588586464,
      "name": "__bpf_skc_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "__bpf_skc_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588723952,
      "name": "__bpf_skc_lookup",
      "external": false,
      "loc": "net/core/filter.c:5258",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_addr_skc_lookup_tcp",
        "net/core/filter.c:bpf_xdp_skc_lookup_tcp",
        "net/core/filter.c:bpf_skc_lookup_tcp",
        "net/core/filter.c:bpf_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588723952,
      "name": "__bpf_skc_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct sock * __bpf_skc_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, struct net * caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags)
```
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int sdif</code>
</li>
</ul>
</details>
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
