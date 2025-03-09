# Function: <code>__udp_gso_segment</code>

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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588416736,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:190",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588416736,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 899
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588608080,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:191",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588608080,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 893
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589019792,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:187",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589019792,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 953
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589244352,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:187",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589244352,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 953
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590218272,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:201",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590218272,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1134
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features, bool is_ipv6)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590268736,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:263",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590268736,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1153
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features, bool is_ipv6)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590183264,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:263",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590183264,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1359
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features, bool is_ipv6)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590964096,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:263",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590964096,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1357
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features, bool is_ipv6)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592605728,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:264",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592605728,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1369
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features, bool is_ipv6)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594469904,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:264",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594469904,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1369
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features, bool is_ipv6)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594861136,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:265",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594861136,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1468
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features, bool is_ipv6)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595672464,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:265",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp_offload.c:udp4_ufo_fragment",
        "net/ipv6/udp_offload.c:udp6_ufo_fragment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595672464,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1468
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502872440,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:187",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502872440,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 892
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235568460,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:187",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235568460,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 872
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296529024,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:187",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296529024,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1144
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278974516,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:187",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278974516,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 806
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588850736,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:187",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588850736,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 953
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588562672,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:187",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588562672,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 953
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589286912,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:187",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589286912,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 953
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features)
```

```json
{
  "name": "__udp_gso_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589328384,
      "name": "__udp_gso_segment",
      "external": true,
      "loc": "net/ipv4/udp_offload.c:187",
      "file": "net/ipv4/udp_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589328384,
      "name": "__udp_gso_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 953
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
struct sk_buff * __udp_gso_segment(struct sk_buff * gso_skb, netdev_features_t features)
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool is_ipv6</code>
</li>
</ul>
</details>
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
