# Function: <code>__udp6_lib_err_encap</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589053534,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:460",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_err"
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
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589506954,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:448",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_err"
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
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589731050,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:448",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_err"
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
struct sock * __udp6_lib_err_encap(struct net * net, const struct ipv6hdr * hdr, int offset, struct udphdr * uh, struct udp_table * udptable, struct sk_buff * skb, struct inet6_skb_parm * opt, u8 type, u8 code, __be32 info)
```

```json
{
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590748848,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:451",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590748848,
      "name": "__udp6_lib_err_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
struct sock * __udp6_lib_err_encap(struct net * net, const struct ipv6hdr * hdr, int offset, struct udphdr * uh, struct udp_table * udptable, struct sk_buff * skb, struct inet6_skb_parm * opt, u8 type, u8 code, __be32 info)
```

```json
{
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590807984,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:502",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590807984,
      "name": "__udp6_lib_err_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590736548,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:501",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_err"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591553150,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:503",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_err"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593242835,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:505",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_err"
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
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595143592,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:520",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_err"
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
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595538534,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:534",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_err"
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
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596381489,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:502",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_err"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503421820,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:448",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_err"
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
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236085016,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:448",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_err"
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
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297202352,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:448",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_err"
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
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279415902,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:448",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_err"
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
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589335418,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:448",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_err"
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
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589060410,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:448",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_err"
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
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589772282,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:448",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_err"
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
  "name": "__udp6_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589822986,
      "name": "__udp6_lib_err_encap",
      "external": false,
      "loc": "net/ipv6/udp.c:448",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_err"
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
struct sock * __udp6_lib_err_encap(struct net * net, const struct ipv6hdr * hdr, int offset, struct udphdr * uh, struct udp_table * udptable, struct sk_buff * skb, struct inet6_skb_parm * opt, u8 type, u8 code, __be32 info)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct sock * __udp6_lib_err_encap(struct net * net, const struct ipv6hdr * hdr, int offset, struct udphdr * uh, struct udp_table * udptable, struct sk_buff * skb, struct inet6_skb_parm * opt, u8 type, u8 code, __be32 info)
```
</details>
</li>
</ul>
