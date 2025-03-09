# Function: <code>ipv6_push_rthdr4</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587840227,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:867",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588001221,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:867",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588537858,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:908",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588902205,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:895",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
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
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589125645,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:895",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589579307,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:891",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589803691,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:891",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ipv6_push_rthdr4(struct sk_buff * skb, u8 * proto, struct ipv6_rt_hdr * opt, struct in6_addr * * addr_p, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590821472,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:1088",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590821472,
      "name": "ipv6_push_rthdr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
void ipv6_push_rthdr4(struct sk_buff * skb, u8 * proto, struct ipv6_rt_hdr * opt, struct in6_addr * * addr_p, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590881488,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:1083",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590881488,
      "name": "ipv6_push_rthdr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
void ipv6_push_rthdr4(struct sk_buff * skb, u8 * proto, struct ipv6_rt_hdr * opt, struct in6_addr * * addr_p, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590810400,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:1083",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590810400,
      "name": "ipv6_push_rthdr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
void ipv6_push_rthdr4(struct sk_buff * skb, u8 * proto, struct ipv6_rt_hdr * opt, struct in6_addr * * addr_p, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591628112,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:1131",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591628112,
      "name": "ipv6_push_rthdr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
void ipv6_push_rthdr4(struct sk_buff * skb, u8 * proto, struct ipv6_rt_hdr * opt, struct in6_addr * * addr_p, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593323424,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:1132",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593323424,
      "name": "ipv6_push_rthdr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
void ipv6_push_rthdr4(struct sk_buff * skb, u8 * proto, struct ipv6_rt_hdr * opt, struct in6_addr * * addr_p, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595228880,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:1132",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595228880,
      "name": "ipv6_push_rthdr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
void ipv6_push_rthdr4(struct sk_buff * skb, u8 * proto, struct ipv6_rt_hdr * opt, struct in6_addr * * addr_p, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595624880,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:1099",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595624880,
      "name": "ipv6_push_rthdr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
void ipv6_push_rthdr4(struct sk_buff * skb, u8 * proto, struct ipv6_rt_hdr * opt, struct in6_addr * * addr_p, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596472304,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:1104",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596472304,
      "name": "ipv6_push_rthdr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503509372,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:891",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236164484,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:891",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297301792,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:891",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279481210,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:891",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589408059,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:891",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589133051,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:891",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589844923,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:891",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_push_rthdr4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589896203,
      "name": "ipv6_push_rthdr4",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:891",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void ipv6_push_rthdr4(struct sk_buff * skb, u8 * proto, struct ipv6_rt_hdr * opt, struct in6_addr * * addr_p, struct in6_addr * saddr)
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
