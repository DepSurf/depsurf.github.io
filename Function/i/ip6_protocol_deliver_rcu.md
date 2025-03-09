# Function: <code>ip6_protocol_deliver_rcu</code>

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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588911616,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:322",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588911616,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1222
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589353776,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:325",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589353776,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1264
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589577904,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:337",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589577904,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1236
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590583120,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:361",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590583120,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1238
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590643536,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:351",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590643536,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1245
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590567904,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:350",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590567904,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1256
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591379648,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:350",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591379648,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1316
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593054160,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:362",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593054160,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1437
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594946864,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:362",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594946864,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1287
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595339520,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:362",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595339520,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1295
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596180240,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:363",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596180240,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1295
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503252864,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:337",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503252864,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1320
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235925892,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:337",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235925892,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1956
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296997440,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:337",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296997440,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1728
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279280854,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:337",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279280854,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1164
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589182272,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:337",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589182272,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1236
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588907264,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:337",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588907264,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1236
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589619136,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:337",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589619136,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1236
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```

```json
{
  "name": "ip6_protocol_deliver_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589667568,
      "name": "ip6_protocol_deliver_rcu",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:337",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589667568,
      "name": "ip6_protocol_deliver_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1236
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
void ip6_protocol_deliver_rcu(struct net * net, struct sk_buff * skb, int nexthdr, bool have_final)
```
</details>
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
