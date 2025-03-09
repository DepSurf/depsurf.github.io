# Function: <code>__ip_options_compile</code>

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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588381152,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:254",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588381152,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1713
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588779664,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:254",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588779664,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1724
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589003248,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:254",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589003248,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1724
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589961440,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:254",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/ip_options.c:ip_options_get",
        "net/ipv4/ip_options.c:ip_options_get_from_user",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589961440,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1739
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590002240,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:254",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/ip_options.c:ip_options_get",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590002240,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1739
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589916448,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:254",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/ip_options.c:ip_options_get",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589916448,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1731
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590682976,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:254",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/ip_options.c:ip_options_get",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590682976,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1731
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592311152,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:241",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/ip_options.c:ip_options_get",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592311152,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1743
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594147840,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:241",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/ip_options.c:ip_options_get",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594147840,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1743
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594535024,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:241",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/ip_options.c:ip_options_get",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594535024,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1707
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595337728,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:241",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_send_dest_unreach",
        "net/ipv4/ip_options.c:ip_options_get",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595337728,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1707
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502609624,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:254",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502609624,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1372
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235315708,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:254",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235315708,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1608
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296202480,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:254",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/ip_options.c:ip_options_get_finish",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296202480,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1932
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278759738,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:254",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/ip_options.c:ip_options_get_finish",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278759738,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1382
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588609632,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:254",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588609632,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1724
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588321616,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:254",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588321616,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1724
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589045808,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:254",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589045808,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1724
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
```

```json
{
  "name": "__ip_options_compile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589084976,
      "name": "__ip_options_compile",
      "external": true,
      "loc": "net/ipv4/ip_options.c:254",
      "file": "net/ipv4/ip_options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure",
        "net/ipv4/ip_options.c:ip_options_compile",
        "net/ipv4/cipso_ipv4.c:cipso_v4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589084976,
      "name": "__ip_options_compile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1724
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
int __ip_options_compile(struct net * net, struct ip_options * opt, struct sk_buff * skb, __be32 * info)
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
