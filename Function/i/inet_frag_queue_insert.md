# Function: <code>inet_frag_queue_insert</code>

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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
```

```json
{
  "name": "inet_frag_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589131680,
      "name": "inet_frag_queue_insert",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:344",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589131680,
      "name": "inet_frag_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
```

```json
{
  "name": "inet_frag_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589355824,
      "name": "inet_frag_queue_insert",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:344",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589355824,
      "name": "inet_frag_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
```

```json
{
  "name": "inet_frag_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590336640,
      "name": "inet_frag_queue_insert",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:344",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590336640,
      "name": "inet_frag_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
```

```json
{
  "name": "inet_frag_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590389472,
      "name": "inet_frag_queue_insert",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:375",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590389472,
      "name": "inet_frag_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
```

```json
{
  "name": "inet_frag_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590305776,
      "name": "inet_frag_queue_insert",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:375",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590305776,
      "name": "inet_frag_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
```

```json
{
  "name": "inet_frag_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591093152,
      "name": "inet_frag_queue_insert",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:377",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591093152,
      "name": "inet_frag_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
```

```json
{
  "name": "inet_frag_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592744304,
      "name": "inet_frag_queue_insert",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:377",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592744304,
      "name": "inet_frag_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
```

```json
{
  "name": "inet_frag_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594615648,
      "name": "inet_frag_queue_insert",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:383",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594615648,
      "name": "inet_frag_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
```

```json
{
  "name": "inet_frag_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595007632,
      "name": "inet_frag_queue_insert",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:383",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595007632,
      "name": "inet_frag_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
```

```json
{
  "name": "inet_frag_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595820352,
      "name": "inet_frag_queue_insert",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:383",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595820352,
      "name": "inet_frag_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
```

```json
{
  "name": "inet_frag_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502994928,
      "name": "inet_frag_queue_insert",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:344",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502994928,
      "name": "inet_frag_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
```

```json
{
  "name": "inet_frag_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235686276,
      "name": "inet_frag_queue_insert",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:344",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235686276,
      "name": "inet_frag_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
```

```json
{
  "name": "inet_frag_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296686496,
      "name": "inet_frag_queue_insert",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:344",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296686496,
      "name": "inet_frag_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
```

```json
{
  "name": "inet_frag_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279072282,
      "name": "inet_frag_queue_insert",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:344",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279072282,
      "name": "inet_frag_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
```

```json
{
  "name": "inet_frag_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588962000,
      "name": "inet_frag_queue_insert",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:344",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588962000,
      "name": "inet_frag_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
```

```json
{
  "name": "inet_frag_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588673936,
      "name": "inet_frag_queue_insert",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:344",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588673936,
      "name": "inet_frag_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
```

```json
{
  "name": "inet_frag_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589398384,
      "name": "inet_frag_queue_insert",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:344",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589398384,
      "name": "inet_frag_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
```

```json
{
  "name": "inet_frag_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589441472,
      "name": "inet_frag_queue_insert",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:344",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589441472,
      "name": "inet_frag_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int inet_frag_queue_insert(struct inet_frag_queue * q, struct sk_buff * skb, int offset, int end)
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
