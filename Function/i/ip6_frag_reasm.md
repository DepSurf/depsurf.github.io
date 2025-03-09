# Function: <code>ip6_frag_reasm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587160986,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:379",
      "file": "net/ipv6/reassembly.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587613654,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:379",
      "file": "net/ipv6/reassembly.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587818263,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:383",
      "file": "net/ipv6/reassembly.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
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
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587975119,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:383",
      "file": "net/ipv6/reassembly.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
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
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588511045,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:384",
      "file": "net/ipv6/reassembly.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
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
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588875273,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:334",
      "file": "net/ipv6/reassembly.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
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
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589098308,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:279",
      "file": "net/ipv6/reassembly.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
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
int ip6_frag_reasm(struct frag_queue * fq, struct sk_buff * skb, struct sk_buff * prev_tail, struct net_device * dev)
```

```json
{
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589551056,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:248",
      "file": "net/ipv6/reassembly.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589551056,
      "name": "ip6_frag_reasm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
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
int ip6_frag_reasm(struct frag_queue * fq, struct sk_buff * skb, struct sk_buff * prev_tail, struct net_device * dev)
```

```json
{
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589775088,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:248",
      "file": "net/ipv6/reassembly.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589775088,
      "name": "ip6_frag_reasm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
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
int ip6_frag_reasm(struct frag_queue * fq, struct sk_buff * skb, struct sk_buff * prev_tail, struct net_device * dev)
```

```json
{
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590795504,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:248",
      "file": "net/ipv6/reassembly.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590795504,
      "name": "ip6_frag_reasm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
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
int ip6_frag_reasm(struct frag_queue * fq, struct sk_buff * skb, struct sk_buff * prev_tail, struct net_device * dev)
```

```json
{
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590854736,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:250",
      "file": "net/ipv6/reassembly.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590854736,
      "name": "ip6_frag_reasm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 827
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
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590783664,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:250",
      "file": "net/ipv6/reassembly.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590783664,
      "name": "ip6_frag_reasm.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 827
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
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591601472,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:250",
      "file": "net/ipv6/reassembly.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591601472,
      "name": "ip6_frag_reasm.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593294320,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:251",
      "file": "net/ipv6/reassembly.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593294320,
      "name": "ip6_frag_reasm.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 897
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
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595198304,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:256",
      "file": "net/ipv6/reassembly.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595198304,
      "name": "ip6_frag_reasm.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 897
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
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595594048,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:256",
      "file": "net/ipv6/reassembly.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595594048,
      "name": "ip6_frag_reasm.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 897
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
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596436928,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:256",
      "file": "net/ipv6/reassembly.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596436928,
      "name": "ip6_frag_reasm.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 895
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
int ip6_frag_reasm(struct frag_queue * fq, struct sk_buff * skb, struct sk_buff * prev_tail, struct net_device * dev)
```

```json
{
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503480600,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:248",
      "file": "net/ipv6/reassembly.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503480600,
      "name": "ip6_frag_reasm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
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
int ip6_frag_reasm(struct frag_queue * fq, struct sk_buff * skb, struct sk_buff * prev_tail, struct net_device * dev)
```

```json
{
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236130984,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:248",
      "file": "net/ipv6/reassembly.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236130984,
      "name": "ip6_frag_reasm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1096
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
int ip6_frag_reasm(struct frag_queue * fq, struct sk_buff * skb, struct sk_buff * prev_tail, struct net_device * dev)
```

```json
{
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297265280,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:248",
      "file": "net/ipv6/reassembly.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297265280,
      "name": "ip6_frag_reasm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1056
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
int ip6_frag_reasm(struct frag_queue * fq, struct sk_buff * skb, struct sk_buff * prev_tail, struct net_device * dev)
```

```json
{
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279454840,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:248",
      "file": "net/ipv6/reassembly.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279454840,
      "name": "ip6_frag_reasm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 798
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
int ip6_frag_reasm(struct frag_queue * fq, struct sk_buff * skb, struct sk_buff * prev_tail, struct net_device * dev)
```

```json
{
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589379456,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:248",
      "file": "net/ipv6/reassembly.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589379456,
      "name": "ip6_frag_reasm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
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
int ip6_frag_reasm(struct frag_queue * fq, struct sk_buff * skb, struct sk_buff * prev_tail, struct net_device * dev)
```

```json
{
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589104448,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:248",
      "file": "net/ipv6/reassembly.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589104448,
      "name": "ip6_frag_reasm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
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
int ip6_frag_reasm(struct frag_queue * fq, struct sk_buff * skb, struct sk_buff * prev_tail, struct net_device * dev)
```

```json
{
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589816320,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:248",
      "file": "net/ipv6/reassembly.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589816320,
      "name": "ip6_frag_reasm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
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
int ip6_frag_reasm(struct frag_queue * fq, struct sk_buff * skb, struct sk_buff * prev_tail, struct net_device * dev)
```

```json
{
  "name": "ip6_frag_reasm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589867312,
      "name": "ip6_frag_reasm",
      "external": false,
      "loc": "net/ipv6/reassembly.c:248",
      "file": "net/ipv6/reassembly.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589867312,
      "name": "ip6_frag_reasm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 837
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
int ip6_frag_reasm(struct frag_queue * fq, struct sk_buff * skb, struct sk_buff * prev_tail, struct net_device * dev)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int ip6_frag_reasm(struct frag_queue * fq, struct sk_buff * skb, struct sk_buff * prev_tail, struct net_device * dev)
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
