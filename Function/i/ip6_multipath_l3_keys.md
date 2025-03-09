# Function: <code>ip6_multipath_l3_keys</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void ip6_multipath_l3_keys(const struct sk_buff * skb, struct flow_keys * keys)
```

```json
{
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588390352,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:1818",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588390352,
      "name": "ip6_multipath_l3_keys",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588765221,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:1950",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_multipath_hash"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588985465,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:1941",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_multipath_hash"
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
void ip6_multipath_l3_keys(const struct sk_buff * skb, struct flow_keys * keys, struct flow_keys * flkeys)
```

```json
{
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589414560,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:2274",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589414560,
      "name": "ip6_multipath_l3_keys",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void ip6_multipath_l3_keys(const struct sk_buff * skb, struct flow_keys * keys, struct flow_keys * flkeys)
```

```json
{
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589638800,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:2280",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589638800,
      "name": "ip6_multipath_l3_keys",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590646032,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:2302",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590646032,
      "name": "ip6_multipath_l3_keys.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590706128,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:2285",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590706128,
      "name": "ip6_multipath_l3_keys.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590631984,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:2292",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590631984,
      "name": "ip6_multipath_l3_keys.constprop.0",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591445136,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:2295",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591445136,
      "name": "ip6_multipath_l3_keys.constprop.0",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593125392,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:2291",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593125392,
      "name": "ip6_multipath_l3_keys.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
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
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595021568,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:2291",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595021568,
      "name": "ip6_multipath_l3_keys.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
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
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595415072,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:2290",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595415072,
      "name": "ip6_multipath_l3_keys.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596256880,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:2292",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596256880,
      "name": "ip6_multipath_l3_keys.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
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
void ip6_multipath_l3_keys(const struct sk_buff * skb, struct flow_keys * keys, struct flow_keys * flkeys)
```

```json
{
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503321344,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:2280",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503321344,
      "name": "ip6_multipath_l3_keys",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void ip6_multipath_l3_keys(const struct sk_buff * skb, struct flow_keys * keys, struct flow_keys * flkeys)
```

```json
{
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235990556,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:2280",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235990556,
      "name": "ip6_multipath_l3_keys",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
void ip6_multipath_l3_keys(const struct sk_buff * skb, struct flow_keys * keys, struct flow_keys * flkeys)
```

```json
{
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297082368,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:2280",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297082368,
      "name": "ip6_multipath_l3_keys",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
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
void ip6_multipath_l3_keys(const struct sk_buff * skb, struct flow_keys * keys, struct flow_keys * flkeys)
```

```json
{
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279338522,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:2280",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279338522,
      "name": "ip6_multipath_l3_keys",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
void ip6_multipath_l3_keys(const struct sk_buff * skb, struct flow_keys * keys, struct flow_keys * flkeys)
```

```json
{
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589243168,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:2280",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589243168,
      "name": "ip6_multipath_l3_keys",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void ip6_multipath_l3_keys(const struct sk_buff * skb, struct flow_keys * keys, struct flow_keys * flkeys)
```

```json
{
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588968160,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:2280",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588968160,
      "name": "ip6_multipath_l3_keys",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void ip6_multipath_l3_keys(const struct sk_buff * skb, struct flow_keys * keys, struct flow_keys * flkeys)
```

```json
{
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589680032,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:2280",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589680032,
      "name": "ip6_multipath_l3_keys",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void ip6_multipath_l3_keys(const struct sk_buff * skb, struct flow_keys * keys, struct flow_keys * flkeys)
```

```json
{
  "name": "ip6_multipath_l3_keys",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589729184,
      "name": "ip6_multipath_l3_keys",
      "external": false,
      "loc": "net/ipv6/route.c:2280",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589729184,
      "name": "ip6_multipath_l3_keys",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void ip6_multipath_l3_keys(const struct sk_buff * skb, struct flow_keys * keys)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void ip6_multipath_l3_keys(const struct sk_buff * skb, struct flow_keys * keys)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void ip6_multipath_l3_keys(const struct sk_buff * skb, struct flow_keys * keys, struct flow_keys * flkeys)
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
void ip6_multipath_l3_keys(const struct sk_buff * skb, struct flow_keys * keys, struct flow_keys * flkeys)
```
</details>
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
