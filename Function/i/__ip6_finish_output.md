# Function: <code>__ip6_finish_output</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __ip6_finish_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__ip6_finish_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589347968,
      "name": "__ip6_finish_output",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:127",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589347968,
      "name": "__ip6_finish_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __ip6_finish_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__ip6_finish_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589572208,
      "name": "__ip6_finish_output",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:127",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589572208,
      "name": "__ip6_finish_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __ip6_finish_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__ip6_finish_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590577200,
      "name": "__ip6_finish_output",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:128",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590577200,
      "name": "__ip6_finish_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __ip6_finish_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__ip6_finish_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590637903,
      "name": "__ip6_finish_output",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:161",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590637472,
      "name": "__ip6_finish_output.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071590637824,
      "name": "__ip6_finish_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __ip6_finish_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__ip6_finish_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590558896,
      "name": "__ip6_finish_output",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:189",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590558896,
      "name": "__ip6_finish_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __ip6_finish_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__ip6_finish_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591370348,
      "name": "__ip6_finish_output",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:170",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591370256,
      "name": "__ip6_finish_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
    },
    {
      "addr": 18446744071592735931,
      "name": "__ip6_finish_output.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ip6_finish_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593044132,
      "name": "__ip6_finish_output",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:172",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_finish_output"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ip6_finish_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594936404,
      "name": "__ip6_finish_output",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:172",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_finish_output"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ip6_finish_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595328791,
      "name": "__ip6_finish_output",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:173",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_finish_output"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ip6_finish_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596169991,
      "name": "__ip6_finish_output",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:191",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_finish_output"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __ip6_finish_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__ip6_finish_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503246600,
      "name": "__ip6_finish_output",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:127",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503246600,
      "name": "__ip6_finish_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int __ip6_finish_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__ip6_finish_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235918476,
      "name": "__ip6_finish_output",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:127",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235918476,
      "name": "__ip6_finish_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __ip6_finish_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__ip6_finish_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296989296,
      "name": "__ip6_finish_output",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:127",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296989296,
      "name": "__ip6_finish_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int __ip6_finish_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__ip6_finish_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279275662,
      "name": "__ip6_finish_output",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:127",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279275662,
      "name": "__ip6_finish_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int __ip6_finish_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__ip6_finish_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589176576,
      "name": "__ip6_finish_output",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:127",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589176576,
      "name": "__ip6_finish_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int __ip6_finish_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__ip6_finish_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588901568,
      "name": "__ip6_finish_output",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:127",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588901568,
      "name": "__ip6_finish_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int __ip6_finish_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__ip6_finish_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589613440,
      "name": "__ip6_finish_output",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:127",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589613440,
      "name": "__ip6_finish_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int __ip6_finish_output(struct net * net, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__ip6_finish_output",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589661760,
      "name": "__ip6_finish_output",
      "external": false,
      "loc": "net/ipv6/ip6_output.c:127",
      "file": "net/ipv6/ip6_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_output.c:ip6_finish_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589661760,
      "name": "__ip6_finish_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int __ip6_finish_output(struct net * net, struct sock * sk, struct sk_buff * skb)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int __ip6_finish_output(struct net * net, struct sock * sk, struct sk_buff * skb)
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
