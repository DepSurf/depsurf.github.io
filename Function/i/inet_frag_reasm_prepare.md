# Function: <code>inet_frag_reasm_prepare</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
```

```json
{
  "name": "inet_frag_reasm_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_frag_reasm_prepare",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:408",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589134197,
      "name": "inet_frag_reasm_prepare.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071589130896,
      "name": "inet_frag_reasm_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
```

```json
{
  "name": "inet_frag_reasm_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589355056,
      "name": "inet_frag_reasm_prepare",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:408",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589355056,
      "name": "inet_frag_reasm_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
```

```json
{
  "name": "inet_frag_reasm_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590335808,
      "name": "inet_frag_reasm_prepare",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:408",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590335808,
      "name": "inet_frag_reasm_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
```

```json
{
  "name": "inet_frag_reasm_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590388480,
      "name": "inet_frag_reasm_prepare",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:439",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590388480,
      "name": "inet_frag_reasm_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
```

```json
{
  "name": "inet_frag_reasm_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590304784,
      "name": "inet_frag_reasm_prepare",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:439",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590304784,
      "name": "inet_frag_reasm_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
```

```json
{
  "name": "inet_frag_reasm_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591092160,
      "name": "inet_frag_reasm_prepare",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:441",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591092160,
      "name": "inet_frag_reasm_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
```

```json
{
  "name": "inet_frag_reasm_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592743168,
      "name": "inet_frag_reasm_prepare",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:441",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592743168,
      "name": "inet_frag_reasm_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 641
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
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
```

```json
{
  "name": "inet_frag_reasm_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594614448,
      "name": "inet_frag_reasm_prepare",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:447",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594614448,
      "name": "inet_frag_reasm_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 641
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
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
```

```json
{
  "name": "inet_frag_reasm_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595006400,
      "name": "inet_frag_reasm_prepare",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:447",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595006400,
      "name": "inet_frag_reasm_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
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
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
```

```json
{
  "name": "inet_frag_reasm_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595819072,
      "name": "inet_frag_reasm_prepare",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:447",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595819072,
      "name": "inet_frag_reasm_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
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
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
```

```json
{
  "name": "inet_frag_reasm_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502996400,
      "name": "inet_frag_reasm_prepare",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:408",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502996400,
      "name": "inet_frag_reasm_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
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
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
```

```json
{
  "name": "inet_frag_reasm_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235685700,
      "name": "inet_frag_reasm_prepare",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:408",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235685700,
      "name": "inet_frag_reasm_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
```

```json
{
  "name": "inet_frag_reasm_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296685424,
      "name": "inet_frag_reasm_prepare",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:408",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296685424,
      "name": "inet_frag_reasm_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 808
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
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
```

```json
{
  "name": "inet_frag_reasm_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279071654,
      "name": "inet_frag_reasm_prepare",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:408",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279071654,
      "name": "inet_frag_reasm_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
```

```json
{
  "name": "inet_frag_reasm_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588961232,
      "name": "inet_frag_reasm_prepare",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:408",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588961232,
      "name": "inet_frag_reasm_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
```

```json
{
  "name": "inet_frag_reasm_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588673168,
      "name": "inet_frag_reasm_prepare",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:408",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588673168,
      "name": "inet_frag_reasm_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
```

```json
{
  "name": "inet_frag_reasm_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589397616,
      "name": "inet_frag_reasm_prepare",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:408",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589397616,
      "name": "inet_frag_reasm_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
```

```json
{
  "name": "inet_frag_reasm_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589440704,
      "name": "inet_frag_reasm_prepare",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:408",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_reasm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589440704,
      "name": "inet_frag_reasm_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
void * inet_frag_reasm_prepare(struct inet_frag_queue * q, struct sk_buff * skb, struct sk_buff * parent)
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
