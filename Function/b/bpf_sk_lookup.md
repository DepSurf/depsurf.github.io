# Function: <code>bpf_sk_lookup</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588122789,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5106",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sock * bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588441824,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5329",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588441824,
      "name": "bpf_sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
struct sock * bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588648352,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5337",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588648352,
      "name": "bpf_sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589520469,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5464",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
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
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589525961,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:6016",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
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
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589423785,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:6118",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
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
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590166057,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:6242",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct sock * bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:6561",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591728208,
      "name": "bpf_sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071594590064,
      "name": "bpf_sk_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
struct sock * bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:6573",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593518112,
      "name": "bpf_sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071596328769,
      "name": "bpf_sk_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
struct sock * bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:6654",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593980896,
      "name": "bpf_sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071596858637,
      "name": "bpf_sk_lookup.cold",
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
struct sock * bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:6744",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594764832,
      "name": "bpf_sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071597783667,
      "name": "bpf_sk_lookup.cold",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct sock * bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502192944,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5337",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502192944,
      "name": "bpf_sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
struct sock * bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234940400,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5337",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234940400,
      "name": "bpf_sk_lookup",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sock * bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295676240,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5337",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295676240,
      "name": "bpf_sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct sock * bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278447986,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5337",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278447986,
      "name": "bpf_sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct sock * bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588255088,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5337",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588255088,
      "name": "bpf_sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
struct sock * bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587967904,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5337",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587967904,
      "name": "bpf_sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
struct sock * bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588586912,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5337",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588586912,
      "name": "bpf_sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
struct sock * bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, u8 proto, u64 netns_id, u64 flags)
```

```json
{
  "name": "bpf_sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588724400,
      "name": "bpf_sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5337",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sk_lookup_udp",
        "net/core/filter.c:bpf_sk_lookup_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588724400,
      "name": "bpf_sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
struct sock * bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, u8 proto, u64 netns_id, u64 flags)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct sock * bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, u8 proto, u64 netns_id, u64 flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct sock * bpf_sk_lookup(struct sk_buff * skb, struct bpf_sock_tuple * tuple, u32 len, u8 proto, u64 netns_id, u64 flags)
```
</details>
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
