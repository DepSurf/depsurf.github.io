# Function: <code>__ip6_rt_update_pmtu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587064976,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:1340",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587064976,
      "name": "__ip6_rt_update_pmtu.part.47",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587517872,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:1351",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587517216,
      "name": "__ip6_rt_update_pmtu.part.50",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu)
```

```json
{
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587721360,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:1359",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587721360,
      "name": "__ip6_rt_update_pmtu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587874402,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:1391",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587873584,
      "name": "__ip6_rt_update_pmtu.part.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu)
```

```json
{
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588397824,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2070",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588397824,
      "name": "__ip6_rt_update_pmtu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu)
```

```json
{
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588760000,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2313",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588760000,
      "name": "__ip6_rt_update_pmtu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu)
```

```json
{
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588980192,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2304",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588980192,
      "name": "__ip6_rt_update_pmtu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu)
```

```json
{
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589427504,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2693",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589427504,
      "name": "__ip6_rt_update_pmtu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 690
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
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589652695,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2699",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589651840,
      "name": "__ip6_rt_update_pmtu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
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
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu, bool confirm_neigh)
```

```json
{
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590666080,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2721",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590666080,
      "name": "__ip6_rt_update_pmtu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
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
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu, bool confirm_neigh)
```

```json
{
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590726288,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2704",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590726288,
      "name": "__ip6_rt_update_pmtu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
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
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu, bool confirm_neigh)
```

```json
{
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590650960,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2713",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590650960,
      "name": "__ip6_rt_update_pmtu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 725
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
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu, bool confirm_neigh)
```

```json
{
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2843",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591459632,
      "name": "__ip6_rt_update_pmtu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
    },
    {
      "addr": 18446744071592738184,
      "name": "__ip6_rt_update_pmtu.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu, bool confirm_neigh)
```

```json
{
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2839",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593142224,
      "name": "__ip6_rt_update_pmtu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
    },
    {
      "addr": 18446744071594625062,
      "name": "__ip6_rt_update_pmtu.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu, bool confirm_neigh)
```

```json
{
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2839",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595039648,
      "name": "__ip6_rt_update_pmtu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
    },
    {
      "addr": 18446744071596359287,
      "name": "__ip6_rt_update_pmtu.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu, bool confirm_neigh)
```

```json
{
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2838",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595433088,
      "name": "__ip6_rt_update_pmtu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 905
    },
    {
      "addr": 18446744071596887884,
      "name": "__ip6_rt_update_pmtu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu, bool confirm_neigh)
```

```json
{
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2840",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596274192,
      "name": "__ip6_rt_update_pmtu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 905
    },
    {
      "addr": 18446744071597812016,
      "name": "__ip6_rt_update_pmtu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503338816,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2699",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503338000,
      "name": "__ip6_rt_update_pmtu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu, bool confirm_neigh)
```

```json
{
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236003988,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2699",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236003988,
      "name": "__ip6_rt_update_pmtu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
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
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297100756,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2699",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297099744,
      "name": "__ip6_rt_update_pmtu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 772
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
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279349868,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2699",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279349142,
      "name": "__ip6_rt_update_pmtu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589257063,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2699",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589256208,
      "name": "__ip6_rt_update_pmtu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
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
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588982055,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2699",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588981200,
      "name": "__ip6_rt_update_pmtu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
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
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589693927,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2699",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589693072,
      "name": "__ip6_rt_update_pmtu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
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
  "name": "__ip6_rt_update_pmtu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589743527,
      "name": "__ip6_rt_update_pmtu",
      "external": false,
      "loc": "net/ipv6/route.c:2699",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:ip6_rt_update_pmtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589742656,
      "name": "__ip6_rt_update_pmtu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 698
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
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu)
```
</details>
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
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu, bool confirm_neigh)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry * dst, const struct sock * sk, const struct ipv6hdr * iph, u32 mtu, bool confirm_neigh)
```
</details>
</li>
</ul>
